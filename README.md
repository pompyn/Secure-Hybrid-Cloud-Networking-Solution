# Secure-Hybrid-Cloud-Networking-Solution
### 🌐 Secure Hybrid Cloud Networking Solution

## Skills Demonstrated

- Azure Virtual Networking
- Hybrid Cloud Architecture
- VLAN Segmentation
- Inter-VLAN Routing
- DHCP Configuration
- Firewall Policy Implementation
- Network Security
- Technical Documentation
- Network Troubleshooting

#### Project Overview

This project demonstrates the design and implementation of a secure hybrid cloud networking solution integrating an on-premises environment with Microsoft Azure. The solution uses VLAN segmentation, firewall policies, DHCP services, and Azure networking components to support secure communication while maintaining separation between departmental workloads.

### Azure Resource Architecture

**Azure Infrastructure**

* Azure Virtual Network (10.1.0.0/16)
* Azure Subnet (10.1.0.0/24)
* Network Security Group (NSG)
* Azure Virtual Machine
* Public IP Address
* Network Interface Card (NIC)
* Managed Disk Resources

#### Environment

**On-Premises Infrastructure**

* GNS3 Network Simulation
* MikroTik CHR Router
* EXOS Layer 2 Switch
* GovOps VLAN
* CivOps VLAN
* ITAdmin VLAN


* Implemented departmental network segmentation using VLANs.
* Configured DHCP services to automate IP address management.
* Configured Layer 3 routing between isolated network segments.
* Applied firewall policies and security controls to restrict unnecessary communication.
* Built Azure virtual networking components supporting hybrid connectivity.
* Validated connectivity and communication paths through structured testing.
* Documented architecture and resource relationships to support future expansion and troubleshooting.

#### Architecture Overview

### On-Premises Network Topology

<img width="630" height="333" alt="onprem-network" src="https://github.com/user-attachments/assets/86abda38-5024-41c2-88ca-4bce03b8f2bc" />
#### Security Features

* VLAN-based network isolation
* Layer 3 routing controls
* Azure Network Security Groups
* Firewall policy enforcement
* Controlled communication between network segments
* Secure hybrid cloud architecture

#### Business Value

* Reduced attack surface through network segmentation.
* Improved security for government and civilian workloads.
* Supported future cloud expansion initiatives.
* Demonstrated hybrid networking concepts used in enterprise and government environments.
* Created a documented and repeatable architecture model for future deployments.

#### Technologies Used

* Microsoft Azure
* Azure Virtual Networks
* Azure Network Security Groups
* GNS3
* MikroTik CHR
* EXOS Switching
* VLANs
* DHCP
* Routing & Switching
* Firewall Policies
* TCP/IP Networking

#### Lessons Learned

* Effective network segmentation significantly reduces security risk.
* Hybrid cloud environments require careful planning of addressing, routing, and access controls.
* Azure NSGs provide flexible cloud-based traffic filtering that complements traditional firewall controls.
* Detailed documentation simplifies troubleshooting, maintenance, and future expansion efforts.
* Designing for scalability early reduces future architectural complexity.

#### Future Enhancements

* Site-to-Site VPN Integration
* Azure VPN Gateway Deployment
* Azure Monitor Integration
* Centralized Logging and SIEM Connectivity
* Identity Integration with Azure Active Directory
* Infrastructure as Code (IaC) Deployment Templates
