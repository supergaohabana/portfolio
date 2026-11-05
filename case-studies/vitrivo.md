# Vitrivo

**Product composition workspace · TypeScript · Node.js · PWA · PostgreSQL**

## Explore

[Open Vitrivo Estudio](https://vitrivo-estudio.web.app/)

Website access checked on November 5, 2026. Account-based features may require access; this check did not validate authentication or synchronization.

## The problem

Creating commerce visuals repeatedly involves the same assets, product combinations and changing catalog information. A useful tool needs to support both composition and the ongoing maintenance of those inputs.

## My contribution

I define the operational workflows and direct AI-assisted development and validation of the composition workspace and catalog integrations.

## Selected work

- Browser-based canvas editing and reusable product assets.
- Product combinations and variants for different operating contexts.
- Catalog synchronization with caching and handling of provider failures.
- Change detection for product combinations whose catalog inputs have drifted.
- Multiuser library synchronization and browser-level workflow checks.

## A decision worth discussing

Repeatedly fetching full records and images can waste bandwidth. The project includes work on lighter synchronization indexes, selective payload retrieval and asset caching. Local improvements must be measured after deployment before claiming production savings.

## Status and limits

The workspace has been deployed and used. Recent synchronization improvements have local validation recorded; this case study makes no claim about their current deployment or measured production savings. Live service availability needs checking before a demo.

## Walkthrough topics

Reusable assets, synchronization failure states and how catalog changes affect a saved composition.

[Back to selected work](../README.md)
