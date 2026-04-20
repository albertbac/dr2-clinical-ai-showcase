# Workflow

```mermaid
graph LR
    A[User intent] --> B[Structured input]
    B --> C[Processing or orchestration]
    C --> D[Reviewable output]
    D --> E[Operational follow-up]
```

## Workflow summary
Users register items, score urgency-gravity-trend, and review the resulting ordering in a persistent workspace.

## Public-safe boundary
This workflow is intentionally high level and does not expose internal decision rules or operating thresholds.
