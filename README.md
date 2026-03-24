# cjr-monorepo

Minimal demo monorepo for catalog-driven service discovery.

## Layout

- `apps/catalog-web`: placeholder frontend service for browsing catalog entries
- `apps/catalog-api`: placeholder backend service for serving catalog data
- `apps/admin-portal`: placeholder internal admin UI for platform operators
- `apps/docs-site`: placeholder docs surface for service onboarding
- `apps/ops-dashboard`: placeholder operational dashboard for support and SRE workflows
- `services/ingestion-worker`: background worker for syncing external systems into the catalog
- `services/auth-service`: placeholder identity and access service
- `services/notification-service`: placeholder service for email and event notifications
- `services/audit-worker`: placeholder async worker for audit/event retention
- `services/search-service`: placeholder search/indexing service for catalog lookups
- `services/billing-service`: placeholder internal billing and usage service
- `packages/shared-config`: shared config and conventions used across services
- `packages/ui-kit`: placeholder shared UI primitives package
- `packages/schemas`: placeholder shared schema contracts package
- `catalog`: sample catalog entities and relationships
- `docs`: short integration notes

## Notes

This repo is intentionally light on implementation. It is meant to look realistic enough for demos and catalog integration work without carrying a full application stack.
