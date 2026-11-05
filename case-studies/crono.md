# CRONO

**Sports timing prototype · Python · SQLite · JavaScript · Simulated RFID**

## The problem

At a finish line, operators need to capture arrivals while correcting participant information and handling uncertain results. A lost response or accidental repeat must not silently turn into a duplicate timing record.

## My contribution

I translate race-operation needs into product requirements and direct AI-assisted implementation and review of the demonstrable timing workflow.

## Implemented demo workflows

- Race and participant management, with validated CSV import.
- Manual timing capture and a simulated RFID gate.
- Corrections with reasons and history, preserving the original timing record.
- Provisional results, public display and exports.
- Local SQLite persistence, backups and explicit interrupted-session recovery.

## A decision worth discussing

A request whose response was lost has an unknown outcome. The interface checks whether a timing record was saved before encouraging another capture. Idempotent requests and visible uncertainty help preserve trustworthy results.

## Evidence and limits

The local product record documents 88 tests and a Chromium walkthrough at the demo delivery stage, including participant management, simulated arrivals, corrections and results. These are historical validation records, not tests rerun for this portfolio.

**Physical reader integration and timing accuracy with real hardware remain unvalidated.** This is a local demonstrable prototype, not a certified timing system or a publicly hosted service.

## Walkthrough topics

Duplicate prevention, audited corrections, recovery and the boundary between simulation and hardware validation.

[Back to selected work](../README.md)
