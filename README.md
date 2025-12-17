# ADR Example Service

This is an example repository demonstrating the use of Architecture Decision Records (ADRs) with Backstage.

## Structure

```
.
├── catalog-info.yaml          # Backstage catalog entity
├── docs/
│   └── adrs/                  # Architecture Decision Records
│       ├── 0001-use-backstage-for-developer-portal.md
│       ├── 0002-adopt-adr-for-architectural-decisions.md
│       └── 0003-use-argocd-for-gitops.md
└── README.md
```

## ADRs

This repository contains the following ADRs:

1. **0001** - Use Backstage for Developer Portal
2. **0002** - Adopt ADR for Architectural Decisions
3. **0003** - Use ArgoCD for GitOps Deployments

## Backstage Integration

The `catalog-info.yaml` file includes the annotation `backstage.io/adr-location: docs/adrs` which enables the ADR plugin to discover and display these records in Backstage.

