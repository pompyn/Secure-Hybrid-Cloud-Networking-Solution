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

## Project Overview

This project demonstrates the design and implementation of a secure hybrid cloud networking solution integrating an on-premises environment with Microsoft Azure. The solution uses VLAN segmentation, firewall policies, DHCP services, and Azure networking components to support secure communication while maintaining separation between departmental workloads.

## Architecture Overview

### On-Premises Network Topology

<img width="630" height="333" alt="onprem-network" src="https://github.com/user-attachments/assets/86abda38-5024-41c2-88ca-4bce03b8f2bc" />

Description

### Azure Resource Architecture

<img width="704" height="652" alt="Azure Resource Architecture" src="https://github.com/user-attachments/assets/da5d143e-76f9-46d8-ac9a-11367c0a0e30" />

Description

## Environment

### On-Premises Infrastructure

...

### Azure Infrastructure

* Azure Virtual Network (10.1.0.0/16)
* Azure Subnet (10.1.0.0/24)
* Network Security Group (NSG)
* Azure Virtual Machine
* Public IP Address
* Network Interface Card (NIC)
* Managed Disk Resources
  The Azure environment extends the on-premises network into the cloud while maintaining security boundaries and supporting future hybrid cloud expansion.

## Key Accomplishments

...

## Security Features

...

## Business Value

* Reduced attack surface through network segmentation.
* Improved security for government and civilian workloads.
* Supported future cloud expansion initiatives.
* Demonstrated hybrid networking concepts used in enterprise and government environments.
* Created a documented and repeatable architecture model for future deployments.


## Technologies Used

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

## Lessons Learned

* Effective network segmentation significantly reduces security risk.
* Hybrid cloud environments require careful planning of addressing, routing, and access controls.
* Azure NSGs provide flexible cloud-based traffic filtering that complements traditional firewall controls.
* Detailed documentation simplifies troubleshooting, maintenance, and future expansion efforts.
* Designing for scalability early reduces future architectural complexity.

## Future Enhancements

* Site-to-Site VPN Integration
* Azure VPN Gateway Deployment
* Azure Monitor Integration
* Centralized Logging and SIEM Connectivity
* Identity Integration with Azure Active Directory
* Infrastructure as Code (IaC) Deployment Templates
