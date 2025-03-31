---
uid: <PRJID>_deployment_infrastructure
---

# Production

The infrastructure for <PRJNAME> is built around a single Dataminer cluster, comprising X DMAs.

| ID       | DMA Name   | Location       | Host       | IP       |
|----------|------------|----------------|------------|----------|
| 123306 | CCC-DMA-PRD-01A | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.165.66.186 |
| 123306 | CCC-DMA-PRD-01B | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.165.66.187 |
| 123307 | CCC-DMA-PRD-02A | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.165.66.189 |
| 123307 | CCC-DMA-PRD-02B | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.165.66.190 |
| 123308 | CCC-DMA-PRD-03A | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.165.66.192 |
| 123308 | CCC-DMA-PRD-03B | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.165.66.193 |
| 4613 | LMC-CTL-PRD-01 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.249 |
| 4613 | LMC-CTL-PRD-02 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.250 |
| 4610 | LMC-DMA-PRD-01 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.200 |
| 4610 | LMC-DMA-PRD-02 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.201 |
| 4612 | LMC-DMA-PRD-03 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.202 |
| 4612 | LMC-DMA-PRD-04 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.203 |
| 123305 | LMC-DMA-PRD-05 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.205 |
| 123305 | LMC-DMA-PRD-06 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.206 |
| 123310 | LMC-DMA-PRD-07 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.208 |
| 123310 | LMC-DMA-PRD-08 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | 10.144.66.209 |

# Storage Infrastructure

<!-- REMOVABLE DESCRIPTION
We can either describe the storage cluster's location and reference other documentation, or we can create a table that illustrates the general information of the nodes.
-->
### Cassandra Nodes
| Server Name      | IP Address     |
|------------------|----------------|
| SLDMADB (CCC-DMA-PRD-01A) | 10.165.66.186 |

# Staging

The infrastructure for <PRJNAME> is built around a single Dataminer cluster, comprising X DMAs.

| ID       | DMA Name   | IP       |
|----------|------------|----------|
| 123304 | lmc-dma-stg-02 | 10.144.66.197 |

# Storage Infrastructure

<!-- REMOVABLE DESCRIPTION
We can either describe the storage cluster's location and reference other documentation, or we can create a table that illustrates the general information of the nodes.
-->
### Cassandra Nodes
| Server Name      | IP Address     |
|------------------|----------------|
| SLDMADB (lmc-dma-stg-02) | 10.144.66.197 |
