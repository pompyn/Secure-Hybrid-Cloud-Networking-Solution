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

The on-premises environment uses VLAN segmentation to separate GovOps, CivOps, and ITAdmin workloads. An EXOS Layer 2 switch provides VLAN functionality while a MikroTik CHR router performs inter-VLAN routing and enforces security policies. This design demonstrates network segmentation, access control, and secure communication between departmental resources.


### Azure Resource Architecture

<img width="704" height="652" alt="Azure Resource Architecture" src="https://github.com/user-attachments/assets/da5d143e-76f9-46d8-ac9a-11367c0a0e30" />

The Azure environment consists of a Virtual Network, subnet, virtual machine, network interface, public IP address, managed disk, and Network Security Group. These resources provide secure cloud-hosted services and establish the foundation for future hybrid connectivity between Azure and the on-premises environment.


## Environment

### On-Premises Infrastructure

* GNS3 Network Simulation
* MikroTik CHR Router
* EXOS Layer 2 Switch
* GovOps VLAN
* CivOps VLAN
* ITAdmin VLAN

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

- Implemented departmental network segmentation using VLANs.
- Configured DHCP services to automate IP address management.
- Configured Layer 3 routing between isolated network segments.
- Applied firewall policies and security controls to restrict unnecessary communication.
- Built Azure virtual networking components supporting hybrid connectivity.
- Validated connectivity and communication paths through structured testing.
- Documented architecture and resource relationships to support future expansion and troubleshooting.

## Validation & Testing

The solution was validated through structured testing including VLAN segmentation verification, DHCP lease validation, routing table inspection, firewall rule testing, and inter-VLAN connectivity testing. Testing artifacts and screenshots were documented as part of the project deliverables.
## Security Features

### VLAN Segmentation Validation

Validation confirmed that VLAN10, VLAN20, and VLAN30 were configured with unique subnets and gateways to maintain network segmentation and controlled communication.

<img width="576" height="159" alt="ip-addressprint" src="https://github.com/user-attachments/assets/d970db6a-5322-43d0-bec2-e7d75d7d97ab" />

### DHCP Validation

DHCP services were configured for VLAN10 (GovOps), VLAN20 (CivOps), and VLAN30 (ITAdmin). Validation confirmed that each VLAN was assigned a dedicated DHCP server and address pool, ensuring automatic IP address allocation within the appropriate network segment.

<img width="584" height="123" alt="DHCP-validation" src="https://github.com/user-attachments/assets/057dfe6f-39c9-443c-8734-41f3cc2898c6" />

### Firewall Policy Validation

Firewall rules were implemented to enforce network segmentation and control communication between departmental VLANs. Validation confirmed that GovOps (VLAN10) was restricted from communicating with CivOps (VLAN20) and ITAdmin (VLAN30), while approved communication between CivOps and ITAdmin networks remained permitted. Administrative access controls were also configured for the ITAdmin network.

<img width="576" height="533" alt="firewall-policy-validation" src="https://github.com/user-attachments/assets/baa01c5c-6c70-47c5-948d-30d09f7cb6f0" />

### Connectivity Validation

Connectivity testing was performed to verify both permitted and restricted communication paths between VLANs. Validation confirmed that approved communication between CivOps (VLAN20) and ITAdmin (VLAN30) succeeded, while firewall policies correctly prevented unauthorized communication from GovOps (VLAN10) to other network segments.

**Allowed Communication**

* VLAN20 → VLAN30: Successful

**Restricted Communication**

* VLAN10 → VLAN20: Blocked
* VLAN10 → VLAN30: Blocked


<img width="589" height="415" alt="VLAN10" src="https://github.com/user-attachments/assets/fa8f795d-8ece-4e45-848d-143e0261c622" />

<img width="578" height="416" alt="VLAN20" src="https://github.com/user-attachments/assets/562d831c-8315-45e5-8659-15342eeefa5b" />

<img width="589" height="407" alt="VLAN30" src="https://github.com/user-attachments/assets/f2d9d4b9-148b-4985-865b-f64a7b4ffc82" />

### Security Features

VLAN Segmentation
Firewall Policies
NSGs
Inter-VLAN Routing Controls
Administrative Separation

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
