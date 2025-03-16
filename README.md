# MPLS Labs in GNS3

This repository contains a set of laboratory exercises focused on MPLS (Multiprotocol Label Switching) implemented in a GNS3 environment. The labs are designed to provide hands-on experience with MPLS concepts, configurations, and troubleshooting.

## Features
- Simulation of MPLS networks in GNS3
- Configuration of MPLS LDP (Label Distribution Protocol)
- Implementation of MPLS VPNs (Layer 2 and Layer 3)
- Traffic engineering with MPLS TE
- MPLS QoS and Fast Reroute (FRR)

## Prerequisites
Before starting the labs, ensure you have the following installed:
- GNS3 (latest version)
- Cisco IOS images with MPLS support (e.g., IOSv, IOS XR, or dynamips-based images)
- Basic knowledge of routing protocols (OSPF, BGP)

## Installation and Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/blazu6/MPLS_lab.git
   cd mpls-gns3-labs
   ```
2. Open GNS3 and import the provided project files.
3. Start the network topology and configure devices according to the lab guides.

## Lab Exercises
The repository includes multiple lab exercises:
1. **Basic MPLS Configuration** – Setting up MPLS LDP and verifying label exchange.
2. **MPLS L3VPN** – Configuring MPLS VPNs with BGP as the control plane.
3. **MPLS L2VPN (VPWS & VPLS)** – Implementing point-to-point and multipoint Layer 2 VPNs.
4. **MPLS Traffic Engineering** – Using RSVP-TE to optimize traffic flows.
5. **MPLS QoS** – Implementing Quality of Service in MPLS networks.

## Usage
- Each lab contains a topology diagram and step-by-step configuration instructions.
- Configuration files for different stages of the labs are provided.
- Wireshark capture files may be included for analysis.

## Contribution
Feel free to submit pull requests with improvements, additional labs, or documentation enhancements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, please open an issue or reach out via email.

