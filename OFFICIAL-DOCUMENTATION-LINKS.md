# Networking ready reckoners - official documentation index

Archify 2.17 does not define a URL or `href` field for architecture components. To preserve deterministic Archify validation, the delivered diagrams keep their boxes non-clickable. This index maps every box to current first-party documentation.

## Google Cloud

| Diagram box | Official documentation |
|---|---|
| VPC network | [VPC overview](https://cloud.google.com/vpc/docs/overview) |
| Subnet | [Subnets](https://cloud.google.com/vpc/docs/subnets) |
| IP addressing | [IP addresses](https://cloud.google.com/vpc/docs/ip-addresses) |
| Firewall controls | [VPC firewall rules](https://cloud.google.com/firewall/docs/firewalls) |
| Workloads | [Compute Engine](https://cloud.google.com/compute/docs/overview), [GKE](https://cloud.google.com/kubernetes-engine/docs/concepts/kubernetes-engine-overview), [Cloud SQL](https://cloud.google.com/sql/docs/introduction) |
| Routes and Cloud Router | [VPC routes](https://cloud.google.com/vpc/docs/routes), [Cloud Router](https://cloud.google.com/network-connectivity/docs/router/concepts/overview) |
| Internet path | [Cloud NAT](https://cloud.google.com/nat/docs/overview), [VPC internet access](https://cloud.google.com/vpc/docs/overview#internet_access) |
| Internet | [VPC internet access](https://cloud.google.com/vpc/docs/overview#internet_access) |
| Private VPC connectivity | [VPC Network Peering](https://cloud.google.com/vpc/docs/vpc-peering), [Network Connectivity Center](https://cloud.google.com/network-connectivity/docs/network-connectivity-center/concepts/overview) |
| Peer networks | [VPC Network Peering](https://cloud.google.com/vpc/docs/vpc-peering) |
| Hybrid connectivity | [Cloud VPN](https://cloud.google.com/network-connectivity/docs/vpn/concepts/overview), [Cloud Interconnect](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/overview) |
| On-prem / multicloud | [Network Connectivity products](https://cloud.google.com/network-connectivity/docs/concepts) |

Scope card: [Google Cloud resource hierarchy](https://cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy) and [regions and zones](https://cloud.google.com/compute/docs/regions-zones).

## Microsoft Azure

| Diagram box | Official documentation |
|---|---|
| Virtual Network | [Azure Virtual Network overview](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview) |
| Subnet | [Manage virtual network subnets](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-subnet) |
| IP addressing | [Public IP addresses](https://learn.microsoft.com/en-us/azure/virtual-network/ip-services/public-ip-addresses), [Private IP addresses](https://learn.microsoft.com/en-us/azure/virtual-network/ip-services/private-ip-addresses) |
| Network Security Group | [Network security groups](https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview) |
| Workloads | [Azure Virtual Machines](https://learn.microsoft.com/en-us/azure/virtual-machines/overview), [AKS](https://learn.microsoft.com/en-us/azure/aks/what-is-aks), [Azure SQL Database](https://learn.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview?view=azuresql) |
| Route table and UDRs | [Virtual network traffic routing](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-udr-overview) |
| Internet path | [NAT Gateway](https://learn.microsoft.com/en-us/azure/nat-gateway/nat-overview), [Public IP addresses](https://learn.microsoft.com/en-us/azure/virtual-network/ip-services/public-ip-addresses) |
| Internet | [Virtual Network internet communication](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview#communicate-with-the-internet) |
| Private connectivity | [Virtual network peering](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview), [Azure Private Link](https://learn.microsoft.com/en-us/azure/private-link/private-link-overview) |
| Private peers | [Virtual network peering](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview), [Azure Private Link](https://learn.microsoft.com/en-us/azure/private-link/private-link-overview) |
| Hybrid connectivity | [VPN Gateway](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways), [ExpressRoute](https://learn.microsoft.com/en-us/azure/expressroute/expressroute-introduction) |
| On-prem / partner edge | [Azure networking overview](https://learn.microsoft.com/en-us/azure/networking/networking-overview) |

Scope card: [Azure resource organization](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/organize-resources) and [availability zones](https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview).

## AWS

| Diagram box | Official documentation |
|---|---|
| Amazon VPC | [VPC basics](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnet-basics.html) |
| Subnet | [Subnets for your VPC](https://docs.aws.amazon.com/vpc/latest/userguide/configure-subnets.html) |
| IP addressing | [IP addressing for VPCs and subnets](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-ip-addressing.html) |
| Security controls | [Security groups](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html), [Network ACLs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html) |
| Workloads | [Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html), [Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html), [Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html) |
| Route tables | [Subnet route tables](https://docs.aws.amazon.com/vpc/latest/userguide/subnet-route-tables.html) |
| Internet path | [Internet Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html), [NAT Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html) |
| Internet | [Internet Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html) |
| Private VPC connectivity | [VPC peering](https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html), [Transit Gateway](https://docs.aws.amazon.com/vpc/latest/tgw/what-is-transit-gateway.html) |
| Peer VPCs | [VPC peering](https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html) |
| Hybrid connectivity | [Site-to-Site VPN](https://docs.aws.amazon.com/vpn/latest/s2svpn/how_it_works.html), [Direct Connect](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html) |
| On-prem / multicloud | [Site-to-Site VPN architecture](https://docs.aws.amazon.com/vpn/latest/s2svpn/how_it_works.html) |

Scope card: [AWS Organizations and OUs](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_ous.html), [AWS Regions](https://docs.aws.amazon.com/global-infrastructure/latest/regions/aws-regions.html), and [Availability Zones](https://docs.aws.amazon.com/global-infrastructure/latest/regions/aws-availability-zones.html).

## Oracle Cloud Infrastructure

| Diagram box | Official documentation |
|---|---|
| Virtual Cloud Network | [VCNs and subnets](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/Overview_of_VCNs_and_Subnets.htm) |
| Subnet | [VCNs and subnets](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/Overview_of_VCNs_and_Subnets.htm) |
| IP addressing | [Private IP addresses](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/managingIPaddresses.htm), [Public IP addresses](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/managingpublicIPs.htm) |
| Security controls | [Security Lists](https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/securitylists.htm), [Network Security Groups](https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/networksecuritygroups.htm) |
| Workloads | [Compute](https://docs.oracle.com/en-us/iaas/Content/Compute/Concepts/computeoverview.htm), [Database](https://docs.oracle.com/en-us/iaas/Content/Database/home.htm), [OKE](https://docs.oracle.com/en-us/iaas/Content/ContEng/Tasks/contengcreatingclusterusingoke.htm) |
| VCN route tables | [VCN Route Tables](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/managingroutetables.htm) |
| Internet path | [Internet Gateway](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/managingIGs.htm), [NAT Gateway](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/NATgateway.htm) |
| Internet | [Internet Gateway](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/managingIGs.htm) |
| Private connectivity | [Service Gateway](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/servicegateway.htm), [Local VCN Peering](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/localVCNpeering.htm) |
| Private peers | [Service Gateway](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/servicegateway.htm), [Local VCN Peering](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/localVCNpeering.htm) |
| Dynamic Routing Gateway | [Dynamic Routing Gateways](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/managingDRGs.htm), [Site-to-Site VPN](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/overviewIPsec.htm), [FastConnect](https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/fastconnect.htm) |
| On-prem / remote VCN | [Site-to-Site VPN](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/overviewIPsec.htm), [Remote VCN Peering](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/remoteVCNpeering.htm) |

Scope card: [Tenancies and compartments](https://docs.oracle.com/en-us/iaas/Content/Identity/Tasks/managingcompartments.htm) and [regions, Availability Domains, and Fault Domains](https://docs.oracle.com/en-us/iaas/Content/General/Concepts/regions.htm).
