---
name: saviynt-analytics-run
description: Fetch a list of analytics controls, retrieve details for a selected control, and execute the analytics control.
api: openapi/saviynt-analytics-api-openapi.yml
operations:
- fetchControlList
- fetchControlDetails
- runAnalyticsControls
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/saviynt-analytics-api-openapi.yml ; every operationId checked against the contract
---

# saviynt-analytics-run

Fetch a list of analytics controls, retrieve details for a selected control, and execute the analytics control.

## Steps

1. 1. `fetchControlList` – POST request to /fetchControlList
2. 2. `fetchControlDetails` – POST request to /fetchControlDetails
3. 3. `runAnalyticsControls` – POST request to /runAnalyticsControls

## Rules

- (none stated)
