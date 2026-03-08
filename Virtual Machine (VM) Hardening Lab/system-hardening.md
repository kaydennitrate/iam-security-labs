Configuring and securing Windows and Linux operating systems within a Type-2 Hypervisor environment to reduce the organizational attack surface.
Technical Specifications
Hypervisor: Oracle VirtualBox
Operating Systems: Windows 10/11, Ubuntu, Kali Linux
Network Mode: Isolated NAT / Host-Only Adapter
Security Controls Implemented
Identity Management: Enforced the Principle of Least Privilege (PoLP) by auditing local user groups and restricting administrative access.
Attack Surface Reduction: Disabled non-essential services and protocols (SMBv1, RDP, NetBIOS) to mitigate lateral movement risks.
System Integrity: Configured local security policies and host-based firewalls to monitor and block unauthorized ingress traffic.
