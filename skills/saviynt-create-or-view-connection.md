---
name: saviynt-create-or-view-connection
description: Create a new connection and then retrieve its details.
api: openapi/saviynt-openapi.yaml
operations:
- createOrUpdate
- getConnectionDetails
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/saviynt-openapi.yaml ; every operationId checked against the contract
---

# saviynt-create-or-view-connection

Create a new connection and then retrieve its details.

## Steps

1. 1. Call `createOrUpdate` with the required request body fields for the connection.
2. 2. Call `getConnectionDetails` with the connection identifier returned from the previous step.

## Rules

- (none stated)
