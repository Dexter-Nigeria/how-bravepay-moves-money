# BravePay Briefings

Plain-language briefings on the BravePay platform: what it is, how it works, and
how it connects to Nigeria's inter-bank payment infrastructure.

## Two briefings

| | For | Read |
|---|---|---|
| **The BravePay Platform** | Management — the whole product, not just banking | https://dexter-nigeria.github.io/how-bravepay-moves-money/report.html |
| **How BravePay Moves Money** | Anyone, no background needed | https://dexter-nigeria.github.io/how-bravepay-moves-money/ |
| **Building BravePay on BankOne** | Product, operations, management | https://dexter-nigeria.github.io/how-bravepay-moves-money/plan.html |
| **Build or Buy the Core** | Anyone asking why we don't build it ourselves | https://dexter-nigeria.github.io/how-bravepay-moves-money/build.html |

Three levels of the same story. The **report** covers all five systems, what is built,
what is measured and what comes next. The **explainer** starts from zero and describes
how money moves. The **plan** covers what changes when we move onto a core banking
platform, what it takes and what has to be answered first. The **decision note**
costs out building a core banking system ourselves — scope, team, timeline and the
four things money cannot compress.

## Who it's for

Anyone who needs to understand the arrangement without a technical background —
board, operations, commercial, customer support, new joiners.

## What the report covers

- **The five systems** and how they fit together
- **What a customer can do** today, and what is waiting on the banking engine
- **The business tools** — invoicing, payroll, expenses — and why they matter commercially
- **Where we are**, honestly: what is running, what is next
- **Quality**, measured before and after
- **What needs deciding** by management

## What the explainer covers

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
