# GCP-Professional-Cloud-Network-Engineer
Notes about the GCP Professional cloud network engineer exam

## VPC

#### 3 types of VPC

<img width="905" alt="Screenshot 2022-02-23 at 14 23 29" src="https://user-images.githubusercontent.com/39993930/155327792-58fc8164-0e0e-44db-9cc4-7a1fcc9ec79a.png">

#### Secondary IP range

Allows containers and other ressources running on a VM to have an IP alias / address  

#### 4 reserves IP / subnet

<img width="935" alt="Screenshot 2022-02-23 at 14 26 45" src="https://user-images.githubusercontent.com/39993930/155328341-3c2bb336-16b5-441f-97f8-d8cdd8bc40c2.png">


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
