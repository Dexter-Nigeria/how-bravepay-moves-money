# How BravePay Moves Money

A plain-language briefing on how BravePay works with its core banking provider and
with NIBSS, Nigeria's inter-bank payment infrastructure, to move money between banks.

**Read it:** https://dexter-nigeria.github.io/how-bravepay-moves-money/

## Who it's for

Anyone who needs to understand the arrangement without a technical background —
board, operations, commercial, customer support, new joiners.

## What it covers

- **Who does what** — BravePay as the shopfront, the core banking system as the back
  office, NIBSS as the road network between banks
- **How the core banking system reaches NIBSS** — and why BravePay inherits that
  connection rather than building one
- **How BravePay connects to the banking engine** — what an API is, and why HTTPS
  (a sealed envelope) matters against HTTP (a postcard)
- **Sending money** — the seven steps, and why writing the instruction down before
  sending it is the most important safety step
- **Receiving money** — how it works, and the notification delay we engineer around
- **What can go wrong** — timeouts, duplicates, partial payroll runs, reversals, and
  the daily reconciliation that catches the rest
- **Glossary** — API, NUBAN, NIP, BVN, settlement, reconciliation, polling

## Note

This is the public, general-audience version. A longer technical blueprint covering
the same arrangement in implementation detail is maintained privately for the
engineering team.

Last updated 3 September 2026.
