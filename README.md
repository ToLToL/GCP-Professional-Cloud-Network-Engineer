# GCP-Professional-Cloud-Network-Engineer
Notes about the GCP Professional cloud network engineer exam

## Hybrid network

#### VLAN attachment

VLAN attachment (interconnect attachment) determines which VPC can reach your om-prem router through an interconnect

Maximum bandwith: 50 GB/s

#### 3 things we need to configure a Direct Peer connection with GCP

1. On-prem publicly routable ASN
2. Publicly routable address space (at least one /24)
3. ASN record completed in PeeringDB

#### Cloud VPN

Maximum bandwith: 3 GB/s
