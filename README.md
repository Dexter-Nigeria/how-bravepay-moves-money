# How BravePay Moves Money

A plain-language briefing on how BravePay works with its core banking provider and
with NIBSS, Nigeria's inter-bank payment infrastructure, to move money between banks.

## Two briefings

| | For | Read |
|---|---|---|
| **How BravePay Moves Money** | Anyone, no background needed | https://dexter-nigeria.github.io/how-bravepay-moves-money/ |
| **Building BravePay on BankOne** | Product, operations, management | https://dexter-nigeria.github.io/how-bravepay-moves-money/plan.html |

The first explains the arrangement from scratch. The second covers what changes,
what we stop building, roughly what it takes, and what has to be answered first.

## Who it's for

Anyone who needs to understand the arrangement without a technical background —
board, operations, commercial, customer support, new joiners.

## What the first briefing covers

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

## What the second briefing covers

- **The decision** — what we stop building and why the line falls where it does
- **Who owns what** — twelve concerns, assigned
- **What we get without building it** — including cards, loans and fixed deposits
- **What is still ours to build** — five things, honestly scoped
- **Three constraints** that shape the work and the cost
- **What happens to each part** of the current product
- **Ten delivery stages** with rough durations, and how to go live safely
- **Risks**, and the questions to answer before stage three

## Note

These are the public, general-audience versions. A longer technical blueprint
covering the same arrangement in implementation detail is maintained privately
for the engineering team.

Last updated 3 September 2026.
