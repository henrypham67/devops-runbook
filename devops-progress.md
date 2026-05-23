# DevOps Progress

> Candid skills tracker. This file is intentionally honest — `GAP` means a real
> gap to close, not a weakness to hide. The coaching workflow reads and updates
> it. Polished, public-facing work lives in `labs/`, `capstones/`, and `adr/`.

**Current target level:** Mid → Senior
**Last updated:** 2026-05-23

## Skill matrix

Legend: ✅ Solid · 🟡 Developing · ❌ GAP

| Group | Skill area | Level | Notes |
| --- | --- | --- | --- |
| A | CI/CD pipelines | 🟡 | |
| A | Containers (Docker) | 🟡 | |
| A | Kubernetes | 🟡 | |
| B | Infrastructure as Code (Terraform) | 🟡 | |
| B | Cloud platform (AWS) | 🟡 | |
| B | Observability (metrics/logs/traces) | 🟡 | |
| C | Reliability / SRE | ❌ GAP | SLOs, error budgets, incident response |
| C | Architecture & judgment | ❌ GAP | Close via `adr/` — design decisions made in public |
| C | Mentoring / leadership | ❌ GAP | |
| C | Security / supply chain | 🟡 | |

## Active focus

- [ ] Close the **Group C** gaps — start by writing ADRs that defend real design decisions.
- [ ] Land the first lab write-up under `labs/`.

## How an entry graduates

1. Do the work → write it up as a lab in `labs/<topic>/README.md`.
2. If it involved a non-trivial design choice → record an ADR in `adr/`.
3. Update the matrix above (level + notes link to the artifact).

## Log

| Date | Entry |
| --- | --- |
| 2026-05-23 | Repo created; progress file initialized. |
