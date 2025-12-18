# 0001. Use Backstage for Developer Portal

Date: 2024-01-15

## Status

Accepted

## Context

We need a centralized platform for developers to discover services, documentation, and tools across our organization. The team evaluated several options including custom solutions, ServiceNow, and Backstage.

## Decision

We will use Backstage as our Developer Portal platform because:

- **Open Source**: Backstage is open-source and backed by Spotify and the CNCF
- **Extensible**: Plugin architecture allows us to integrate with our existing tools
- **Software Catalog**: Built-in catalog for tracking all software components
- **TechDocs**: Integrated documentation system
- **Templates**: Scaffolder for creating new projects consistently
- **Community**: Large and active community with many plugins available

## Consequences

### Positive

- Unified view of all services and their ownership
- Standardized documentation across teams
- Faster onboarding for new developers
- Better discoverability of internal tools and services
- test

### Negative

- Requires maintenance and updates
- Learning curve for teams to adopt
- Need to develop custom plugins for specific integrations
