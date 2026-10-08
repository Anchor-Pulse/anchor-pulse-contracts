# Contract architecture

## Responsibility

An operations dashboard for tracking anchor endpoint availability, response latency, quote freshness, and service-status changes without custodying user funds.

## Security boundary

Every state-changing operation must authenticate the actor that is allowed to cause
the change. Contract storage is intentionally smaller than the application database.

## Future specification

The generic development contract in this baseline must be replaced with the
project-specific state model before production deployment.
