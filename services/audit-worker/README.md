# audit-worker

Placeholder worker for retaining audit records and processing activity streams.

## Intended responsibility

- consume catalog and auth events
- normalize audit trails for demo reporting
- simulate background retention workflows

## Configuration

| Variable | Default | Description |
|---|---|---|
| `POLL_INTERVAL_MS` | `2000` | How often the worker polls the queue |
| `LOG_LEVEL` | `info` | Log verbosity |
