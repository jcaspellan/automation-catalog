# Azure Automation Catalog

A curated catalog of automation assets built for Azure operations, governance, reporting, and remediation.

Each automation includes two implementation variants:

- **Azure Automation Runbook** – for managed, scheduled, cloud-hosted execution
- **Local Script** – for ad hoc execution, testing, debugging, and pipeline use

## Catalog

| Automation | Category | Runbook | Local Script | Status |
|---|---|---:|---:|---|
| [VM Health Check](./automations/vm-health-check) | Operations Readiness | ✅ | ✅ | Stable |
| [Orphaned Resource Cleanup](./automations/orphaned-resource-cleanup) | Cost Optimization | ✅ | ✅ | Draft |

## Documentation Site

Published with GitHub Pages from the `/docs` folder.

## Repository Standards

Each automation includes:

- Overview
- Business value
- Architecture
- Runbook implementation
- Local script implementation
- Inputs and outputs
- Required permissions
- Sample execution
- Version history