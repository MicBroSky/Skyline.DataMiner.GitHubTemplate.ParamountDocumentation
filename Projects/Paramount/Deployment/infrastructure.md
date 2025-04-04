---
uid: <PRJID>_deployment_infrastructure
---

# Production

The infrastructure for Paramount Production is built around a single Dataminer cluster, comprising 16 DMAs.

| ID       | DMA Name   | Location       | Host       |FQDN | Virtual IP  | IP       |
|----------|------------|----------------|------------|----------|----------|----------|
| 4610 | LMC-DMA-PRD-01 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta| lmc-dma-prd-01.mtvn.ad.viacom.com |10.144.66.199 |10.144.66.200 |
| 4610 | LMC-DMA-PRD-02 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-dma-prd-02.mtvn.ad.viacom.com |10.144.66.199 |10.144.66.201 |
| 4612 | LMC-DMA-PRD-03 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-dma-prd-03.mtvn.ad.viacom.com | 10.144.66.204|10.144.66.202 |
| 4612 | LMC-DMA-PRD-04 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-dma-prd-04.mtvn.ad.viacom.com | 10.144.66.204|10.144.66.203 |
| 123305 | LMC-DMA-PRD-05 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-dma-prd-05.mtvn.ad.viacom.com | 10.144.66.207 |10.144.66.205 |
| 123305 | LMC-DMA-PRD-06 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-dma-prd-06.mtvn.ad.viacom.com | 10.144.66.209 |10.144.66.206 |
| 123310 | LMC-DMA-PRD-07 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-dma-prd-07.mtvn.ad.viacom.com | 10.144.66.210 |10.144.66.208 |
| 123310 | LMC-DMA-PRD-08 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-dma-prd-08.mtvn.ad.viacom.com | 10.144.66.210 |10.144.66.209 |
| 123306 | CCC-DMA-PRD-01A | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | CCC-DMA-PRD-01A.mtvn.ad.viacom.com| 10.165.66.185 |10.165.66.186 |
| 123306 | CCC-DMA-PRD-01B | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | CCC-DMA-PRD-01B.mtvn.ad.viacom.com | 10.165.66.185 |10.165.66.187 |
| 123307 | CCC-DMA-PRD-02A | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | CCC-DMA-PRD-02A.mtvn.ad.viacom.com | 10.165.66.188 |10.165.66.189 |
| 123307 | CCC-DMA-PRD-02B | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | CCC-DMA-PRD-02B.mtvn.ad.viacom.com | 10.165.66.188 |10.165.66.190 |
| 123308 | CCC-DMA-PRD-03A | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | CCC-DMA-PRD-03A.mtvn.ad.viacom.com | 10.165.66.191 |10.165.66.192 |
| 123308 | CCC-DMA-PRD-03B | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | CCC-DMA-PRD-03B.mtvn.ad.viacom.com | 10.165.66.191 |10.165.66.193 |
| 4613 | LMC-CTL-PRD-01 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-ctl-prd-01.mtvn.ad.viacom.com |10.144.66.251|10.144.66.249 |
| 4613 | LMC-CTL-PRD-02 | ccc-ny-habvsvcs1.mtvn.ad.viacom.com | vpn.gb.vimn.com/vendormfa-okta | lmc-ctl-prd-02.mtvn.ad.viacom.com |10.144.66.251|10.144.66.250 |


# Storage Infrastructure

<!-- REMOVABLE DESCRIPTION
We can either describe the storage cluster's location and reference other documentation, or we can create a table that illustrates the general information of the nodes.
-->
### Cassandra Nodes
| Server Name      | IP Address     |
|------------------|----------------|
| SLDMADB (LMC-DMA-PRD-01) | 10.144.66.200 |
| SLDMADB (LMC-DMA-PRD-02) | 10.144.66.201 |
| SLDMADB (LMC-DMA-PRD-03) | 10.144.66.202 |
| SLDMADB (LMC-DMA-PRD-04) | 10.144.66.203 |
| SLDMADB (LMC-DMA-PRD-05) | 10.144.66.205 |
| SLDMADB (LMC-DMA-PRD-06) | 10.144.66.206 |
| SLDMADB (LMC-DMA-PRD-07) | 10.144.66.208 |
| SLDMADB (LMC-DMA-PRD-08) | 10.144.66.209 |
| SLDMADB (CCC-DMA-PRD-01A) | 10.165.66.186 |
| SLDMADB (CCC-DMA-PRD-01B) | 10.165.66.187 |
| SLDMADB (CCC-DMA-PRD-02A) | 10.165.66.189 |
| SLDMADB (CCC-DMA-PRD-02B) | 10.165.66.190 |
| SLDMADB (CCC-DMA-PRD-03A) | 10.165.66.192 |
| SLDMADB (CCC-DMA-PRD-03B) | 10.165.66.193 |
| SLDMADB (LMC-CTL-PRD-01) | 10.144.66.249 |
| SLDMADB (LMC-CTL-PRD-02) | 10.144.66.250 |

# Staging

The infrastructure for Paramount Staging is built around a single Dataminer cluster, comprising of a single DMA.

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
