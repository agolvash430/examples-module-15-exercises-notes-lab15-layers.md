# Lab 15 — Transition Matrix

| From     | To      | Allowed?              |
| -------- | ------- | --------------------- |
| PROSPECT | ACTIVE  | yes (Ravi)            |
| ACTIVE   | ACTIVE  | reject (per policy)  |
| ACTIVE   | PROSPECT| no                    |

## Amina (CUS-1001)
Already ACTIVE — activate request is rejected/no-op per policy.

## Illegal list
1. ACTIVE → PROSPECT
2. ACTIVE → ACTIVE (if treated as reject)

## Boundary
Lab that maps exceptions to HTTP: Lab 16

## Scope
Pre-lab only.
