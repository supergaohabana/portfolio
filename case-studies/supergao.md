# SuperGao

**Property platform · React / TypeScript · Flutter · Python · PostgreSQL**

## Explore

[View SuperGao Cuba on Google Play](https://play.google.com/store/apps/details?id=com.supergaohabana.app) · [Open the web app](https://supergao-cuba-web.web.app/)

Public listing and website access checked on November 5, 2026. Android installation eligibility depends on Google Play availability for the visitor. This check did not validate installation or authenticated application workflows.

## The problem

Property discovery involves more than listing cards: users need account access, consistent property information and practical publishing and management workflows across devices.

## My contribution

I drive the product requirements and work with AI coding agents on implementation, iteration and validation across the mobile app, web interface and Python backend.

## Selected work

- Mobile application built with Flutter, alongside a React and TypeScript web interface.
- Python API services connecting application workflows and stored property data.
- A separate web administration panel connected to the backend, with authenticated access and server-side role checks.
- Account and profile flows, property forms and location selection.
- Validation of loading, failure and recovery states, including account changes during requests.

## Administration alongside the customer product

The project includes a separate administrative interface for operating the platform. It connects to the existing backend and uses authenticated access with roles checked by the server. This extends the product beyond its customer-facing mobile and web applications.

Administrative access is not published as a public demo. This portfolio does not claim that every administration workflow has been freshly validated.

## A decision worth discussing

A location editor must distinguish an unchanged location from an explicitly removed one. It must also avoid substituting an approximate public location for a private editable coordinate. These distinctions affect both the interface and the API payload.

## Status and limits

This is an actively developed product with deployed components. Web and mobile feature parity is incomplete; some newer web features are implemented locally and await live validation. Live availability should be checked before a demonstration. This case study does not claim every described workflow is currently available in production.

## Walkthrough topics

Property forms, API contracts, account transitions and the difference between local tests and live validation.

## Tools in this project

Flutter/Dart; React/TypeScript/Vite; Python/aiohttp; PostgreSQL and Supabase Auth/RLS; Render and Firebase Hosting; Cloudinary; Groq API; Telegram Bot API; Google Play Console and Android ADB; Firebase Analytics/Crashlytics/Cloud Messaging; Leaflet; Playwright, Vitest and Flutter tests. Claude Design supported interface exploration. See the inventory for component-specific limits.

[Explore the full tool inventory](../technologies.md)

[Back to selected work](../README.md)
