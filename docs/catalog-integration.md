# Catalog Integration Notes

This demo repo is designed to plug into a service catalog quickly.

## Suggested starting points

- ingest YAML from the `catalog` directory directly into a demo Backstage instance
- map each service `service.yaml` file into a source record for custom catalog tooling
- use `packages/shared-config` as the place for schema rules if the demo grows

## Why the structure is split this way

- `apps` holds user-facing or request-serving surfaces
- `services` holds background or asynchronous processes
- `packages` holds shared internal assets
- `catalog` holds the catalog-facing source-of-truth examples
