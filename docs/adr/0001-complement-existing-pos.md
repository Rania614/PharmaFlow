# ADR-0001: Complement the existing POS

- **Status:** Accepted
- **Date:** 2026-11-18

## Context

The pharmacy already runs a POS for sales, pricing and stock display. Replacing it would be high-risk, and no evidence shows it is needed.

## Decision

The PharmaFlow MVP will not rebuild cashier or sales functionality. It will complement the POS where research shows gaps.

## Consequences

- PharmaFlow depends on getting data out of the POS, which makes integration the top technical risk.
- Counter workflows stay untouched.

## Revisit when

Research shows the POS cannot provide the data PharmaFlow needs, or the owner asks to replace it.
