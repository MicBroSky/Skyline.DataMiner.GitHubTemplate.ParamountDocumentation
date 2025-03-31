---
uid: <PRJID>_deployment_deployment
---

# High-Level Design Overview
<!-- REMOVABLE DESCRIPTION
We have been using two forms to provide a high-level overview of the solution's deployment. Most commonly, we include a
textual description of the system's components and a package diagram that contains a brief summary of each component.
-->
## Staging and Production

The Paramount project comprises of two DMS clusters, Production and Staging, each configured as detailed below and offering
specific features outlined in [value delivery](xref:<PRJID>_overview_overview).

## Production
The DataMiner System (DMS) contains 8 agents configured in a failover pair.   It provides standard monitoring
and control functionality listed in the [delivery features](xref:<PRJID>_overview_overview#delivered-value) section.

## Staging
The DataMiner System (DMS) contains a single agent. It is used for testing new protocol versions, elements, and other configurations listed in the [delivery features](xref:<PRJID>_overview_overview#delivered-value) section.