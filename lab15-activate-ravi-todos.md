# Lab 15 — Fill Activate Ravi Pseudocode TODOs

customer = repo.findById(CUS-1002)
if customer is null → throw NotFound
if status is not PROSPECT → throw IllegalTransition
set status to ACTIVE
repo.save(customer)
log correlation lab-request-001

## Repo boundary
Repo only persists the updated customer; service owns transition validation and exceptions.

## Scope
Pre-lab only.
