# Fantasia Workflow Maps

These public workflow maps explain how Fantasia works without exposing private source code, credentials, endpoints, adapter logic, or implementation details.

## Real Product Screenshots

Use the actual screenshots page for visuals of what exists now:

- [Actual Product Screenshots](PRODUCT_SCREENSHOTS.md)

The maps below are diagrams only. They are not mockups of app screens.

## How Fantasia Works

```mermaid
flowchart LR
  A["Brief"] --> B["Local Session"]
  B --> C["Review Queue"]
  C --> D["Receipts"]
  D --> E["Guarded Adapter"]
  E --> F["Rollback Ready"]
  F --> G["Approved Output"]
```

This is the public version of the flow. It shows the product promise: local work, review, receipts, controlled publishing, and rollback readiness.

## Publish Safety

```mermaid
flowchart TD
  A["Candidate Change"] --> B{"Quality Pass?"}
  B -- "No" --> C["Request Changes"]
  B -- "Yes" --> D{"Receipt Present?"}
  D -- "No" --> C
  D -- "Yes" --> E{"Target Confirmed?"}
  E -- "No" --> C
  E -- "Yes" --> F{"Rollback Ready?"}
  F -- "No" --> C
  F -- "Yes" --> G["Guarded Publish Eligible"]
```

This map intentionally avoids naming real production adapters or endpoints. It communicates the guardrails without giving away the internal recipe.

## Owner Control Loop

```mermaid
flowchart LR
  A["Owner Intent"] --> B["Local Work"]
  B --> C["Visible State"]
  C --> D["Decision"]
  D --> E["Receipt"]
  E --> F["Reversible Action"]
  F --> A
```

Fantasia is designed around owner control: know what happened, decide what moves, keep receipts, and stay able to reverse.

## Public Boundary

These maps do not include:

- private source architecture
- endpoint names
- credentials or signing material
- private local paths
- customer data
- implementation-specific adapter logic
- production runbooks

Use them for GitHub, investor overview, pitch materials, and public product explanation only as workflow diagrams.
