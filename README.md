# Secure-Hybrid-Cloud-Networking-Solution
### 🌐 Secure Hybrid Cloud Networking Solution

* **Skills:** Azure Virtual Networking, Hybrid Cloud Architecture, VLAN Segmentation, Routing & Switching, DHCP, Firewall Policy Enforcement, Network Security Groups (NSGs), Network Troubleshooting, Technical Documentation, Cloud Infrastructure

#### Project Overview

Designed and implemented a secure hybrid cloud networking solution using Azure and GNS3 to support both government and civilian workloads while maintaining network segmentation and secure communication between environments. The architecture demonstrates hybrid connectivity, departmental isolation through VLANs, Layer 3 routing, and cloud-based network security controls.

#### Environment

**On-Premises Infrastructure**

* GNS3 Network Simulation
* MikroTik CHR Router
* EXOS Layer 2 Switch
* GovOps VLAN
* CivOps VLAN
* ITAdmin VLAN
* <img width="630" height="333" alt="onprem-network" src="https://github.com/user-attachments/assets/19f6a056-e0c4-435f-b352-3a7691ec5105" />


**Azure Infrastructure**

* Azure Virtual Network (10.1.0.0/16)
* Azure Subnet (10.1.0.0/24)
* Network Security Group (NSG)
* Azure Virtual Machine
* Public IP Address
* Network Interface Card (NIC)
* Managed Disk Resources
* <img width="704" height="652" alt="Azure-Resource-Architecture" src="https://github.com/user-attachments/assets/eec33e9f-34b2-47ff-8582-9b52b4b7e9d5" />


#### Key Accomplishments

* Implemented departmental network segmentation using VLANs.
* Configured DHCP services to automate IP address management.
* Configured Layer 3 routing between isolated network segments.
* Applied firewall policies and security controls to restrict unnecessary communication.
* Built Azure virtual networking components supporting hybrid connectivity.
* Validated connectivity and communication paths through structured testing.
* Documented architecture and resource relationships to support future expansion and troubleshooting.

#### Architecture Overview

The on-premises environment consists of three departmental VLANs connected through a Layer 3 router and integrated with Azure resources through hybrid connectivity. The Azure environment utilizes a Virtual Network, secured subnet, and Network Security Group to host cloud workloads while maintaining secure communication with on-premises resources.

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
