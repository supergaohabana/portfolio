# Pescadería 19 y B

**Commerce & operations management demo · React · TypeScript · PostgreSQL · Server-side functions**

## Explore

[Open the presentation demo](https://pescaderia-19-y-b.web.app/)

This is a presentation environment, not an open commercial store. Orders are restricted to test accounts. Public page access was checked on November 5, 2026; no orders or inventory changes were made for this portfolio.

## The problem

A small retailer needs more than a storefront. The team must handle orders, substitutions, stock reservations, delivery and exceptions without losing track of who did what.

## My contribution

I define the operating workflows and interface direction, prioritize the first version and work with AI coding agents on frontend, backend integration and validation. My experience in operations informs how the system presents the next action and records exceptions.

## Implemented workflows

- **Customer storefront:** product catalog, basket, order submission and order tracking within the test environment.
- **Order operations:** searchable queues, status filters, approval and preparation, collection or delivery, substitutions, cancellation and incident handling.
- **Inventory:** physical, reserved and available quantities; receipts, losses and counts; movement history with responsible user, reason and before/after quantities.
- **Delivery coordination:** courier assignment, revocable delivery links and confirmation workflows.
- **Administrative records:** order history, receipts, refund records and commercial summaries. Recording payments or refunds is not the same as executing a banking transaction.

## A decision worth discussing

Inventory needs to distinguish physical stock from reserved and available quantities. A repeated adjustment request must not create a second movement. The implementation includes transaction controls, idempotent adjustments and recovery after a lost response or page reload.

The operations interface also preserves the selected order and unfinished input when new orders arrive, so a live queue does not interrupt the task in progress.

## Evidence and status

Project records document database and application checks, mobile and desktop browser exercises, and selected remote API validation. These historical checks were not rerun for this portfolio update.

The demo uses illustrative stock, costs and offers, and AI-generated product imagery. A commercial pilot still requires real operating data and completion of launch checks. Processing whole fish into cuts and related yield/waste accounting remain pending.

This is a focused commerce and operations management system; it is not presented as a complete enterprise ERP.

## Walkthrough topics

Order queues, stock reservations, audited adjustments, interruption recovery and interface design for daily operations. Administrative workflows require an authorized walkthrough; no credentials are published.

[Back to selected work](../README.md)
