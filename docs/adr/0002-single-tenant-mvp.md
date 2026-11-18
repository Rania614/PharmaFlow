# ADR-0002: Single-tenant, single-location MVP

- **Status:** Accepted
- **Date:** 2026-11-18

## Context

The product serves one pharmacy at one physical location.

## Decision

No tenant IDs and no branch model in the MVP schema or authentication.

## Consequences

- The schema and access control stay simpler.
- Supporting multiple tenants later would require a migration. That cost is accepted.

## Revisit when

A second pharmacy or branch becomes a real, committed requirement.
