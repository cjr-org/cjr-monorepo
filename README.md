# cjr-monorepo

Minimal demo monorepo for catalog-driven service discovery.

## Layout

- `apps/catalog-web`: placeholder frontend service for browsing catalog entries
- `apps/catalog-api`: placeholder backend service for serving catalog data
- `services/ingestion-worker`: background worker for syncing external systems into the catalog
- `packages/shared-config`: shared config and conventions used across services
- `catalog`: sample catalog entities and relationships
- `docs`: short integration notes

## Notes

This repo is intentionally light on implementation. It is meant to look realistic enough for demos and catalog integration work without carrying a full application stack.
