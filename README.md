# PharmaFlow

**Pharmacy Operations & Intelligence Platform** (working category) for a single, real community pharmacy.

> **Status: Phase 0 — Discovery & Setup.**
> The business problem has not been validated yet. There is no application code in this repository yet, by design.

## What PharmaFlow is (preliminary)

PharmaFlow aims to help a pharmacy improve its operational visibility and management through useful digital tools and insights. It is intended to **complement** the pharmacy's existing POS system, not replace it. This direction is a hypothesis and will be revisited after research.

## Fixed scope decisions

| Decision | Status |
|---|---|
| One pharmacy, one physical location | Accepted |
| Complement the existing POS; no cashier/sales rebuild | Accepted |
| No multi-tenant SaaS, no multi-branch in MVP | Accepted |
| Requirements only from validated research findings | Accepted |

## Candidate tech stack (not committed)

TypeScript · React + Vite · Material UI · Node.js + Express · PostgreSQL + Prisma · REST · Vitest, React Testing Library, Playwright · Docker · GitHub Actions.

GraphQL/Apollo and Zustand are **deferred** until a real requirement justifies them. See [`docs/adr`](docs/adr).

## Repository layout

```
docs/
  product-vision.md        Vision summary (full version in Notion)
  discovery/               Interview guide
  adr/                     Architecture Decision Records
  jira/                    Discovery backlog CSV for Jira import
.github/                   Issue and pull request templates
```

Planned when development starts: `client/` (React app) and `server/` (API).

## Project links

- **Notion workspace:** PharmaFlow (product, discovery, BA, UX, technical, PM docs)
- **Jira:** project key `KAN`
- **GitHub:** this repository

## Conventions

See [CONTRIBUTING.md](CONTRIBUTING.md).
