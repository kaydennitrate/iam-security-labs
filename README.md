Implementation of security baselines for a SOHO network environment using a Huawei EchoLife ONT. The primary objective was to establish a verifiable asset inventory and monitor for unauthorized network activity.
Technical Specifications
Hardware: Huawei EchoLife ONT Terminal
Protocols: DHCP, DNS, IPv4, ICMP
Monitoring: Gateway Syslog Analysis, DNS-level Filtering
Security Controls Implemented
Asset Identification: Configured Static DHCP Reservations to ensure persistent identity for all authorized network devices.
Access Control: Deployed MAC Address Whitelisting to enforce a Zero-Trust approach for physical layer connections.
Threat Mitigation: Implemented upstream DNS filtering to prevent resolution of known malicious domains and C2 infrastructure.
