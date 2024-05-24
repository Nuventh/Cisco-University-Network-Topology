# University Network Topology

## Introduction
This repository contains the design and configuration files for a university network topology created using Cisco Packet Tracer. The network ensures connectivity and security across various departments and faculties within the university.

## Network Components
- **Building A**: Management, HR, Finance, Faculty of Business
- **Building B**: Faculty of Engineering and Computing, Faculty of Art and Design
- **Building C**: Student Labs, IT Department (with Web Server)
- **Smaller Campus**: Faculty of Health and Sciences
- **External Email Server**: Hosted on the cloud

## Configuration Details
- **VLANs**: Implemented for each department and faculty
- **Routing**: RIPv2 for internal routing, static routing for external server
- **DHCP**: Router-based DHCP for dynamic IP addressing
- **Port Security**: Implemented on switches to control access and prevent unauthorized connections
- **SSH**: Configured on network devices for secure remote access
- **WLAN**: Wireless networks for device connectivity
- **Access Points**: Configured with SSIDs and security settings
- **Host Configurations**: Devices configured with appropriate IP settings

## Files
- **main.pkt**: The Cisco Packet Tracer file of the network topology.

## Usage
1. Open `main.pkt` in Cisco Packet Tracer.
2. Test and verify the network using provided instructions.

## Testing
- Verify VLAN assignments and DHCP bindings.
- Test inter-VLAN and external connectivity.

## Conclusion
This repository provides a comprehensive network topology for a university, ensuring robust and secure communication across all departments and faculties.
