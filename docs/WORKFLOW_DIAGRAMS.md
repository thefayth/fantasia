# Workflow Diagrams

These diagrams are public-safe explanations. They do not expose source code, private prompts, agent instructions, credentials, endpoints, adapter logic, or production runbooks.

## Workflow Overview

```mermaid
flowchart LR
  A["Owner Intent"] --> B["Local Session"]
  B --> C["Review Surface"]
  C --> D["Receipt"]
  D --> E["Guarded Boundary"]
  E --> F["Rollback Ready"]
  F --> G["Public-Safe Output"]
```

Source file: [workflow-overview.mmd](../assets/diagrams/workflow-overview.mmd)

SVG: [workflow-overview.svg](../assets/diagrams/workflow-overview.svg)

## Public / Private Boundary

```mermaid
flowchart LR
  A["Public Repo"] --> B["Project Story"]
  A --> C["Workflow Diagrams"]
  A --> D["Safe Screenshots"]
  E["Private Engine"] --> F["Source Code"]
  E --> G["Prompts and Agents"]
  E --> H["Credentials and Adapters"]
  E --> I["Customer and Operational Data"]
```

Source file: [public-private-boundary.mmd](../assets/diagrams/public-private-boundary.mmd)

SVG: [public-private-boundary.svg](../assets/diagrams/public-private-boundary.svg)

## Safety Notes

These diagrams explain the public product promise:

- visible workflow
- review points
- receipts
- guarded boundary
- rollback readiness
- public/private separation

They intentionally do not document internal implementation.
