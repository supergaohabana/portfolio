# Commerce automation

**Operational reporting · Python · Playwright · pandas · openpyxl**

## The problem

Inventory, sales and availability often live in different systems. A product being active in the catalog does not necessarily mean it can be sold from a particular warehouse.

## My contribution

My business role supplies the operational context. I work with AI coding agents to implement extraction, reconciliation and reporting workflows, then review their output against the underlying business rules.

## Selected work

- Inventory extraction from a web-based business system.
- Recurring reports that reconcile product and warehouse information.
- Spreadsheet generation for operational analysis.
- Checks for availability inconsistencies across catalog and warehouse records.

## A decision worth discussing

Availability should be evaluated at the level where the sale is fulfilled. Checking a global product flag alone can miss warehouse-specific restrictions. The reporting workflow makes these distinctions visible instead of treating every active product as available.

## Quality investigations

Project work includes investigating discrepancies between global product activation and warehouse availability, comparing management-system records with public API output, and checking whether apparently successful HTTP responses actually confirmed a saved operation.

GA4 and operational data help establish scope and context; browser and API checks help reproduce behavior. Analytics correlations alone are not treated as proof of a software defect or its cause.

## Status and boundaries

These workflows support business operations. Client data, credentials, internal endpoints and commercial figures are excluded. Any demonstration should use synthetic or approved data. No quantified time or revenue improvement is claimed without a measured baseline.

## Tools in this project

Python, Playwright, GA4 and Google Analytics Data API, Google Drive and Sheets APIs, OAuth/service accounts, Gemini API, openpyxl, ReportLab, python-docx, BeautifulSoup and pandas across the reporting toolchain. GitHub Actions and launchd support different scheduled workflows.

[Explore the full tool inventory](../technologies.md)

[Back to selected work](../README.md)
