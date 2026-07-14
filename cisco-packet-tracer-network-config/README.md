# Cisco Packet Tracer — Enterprise Network Configuration

Designed and deployed a simulated multi-department enterprise network (Admin, Sales, HR) with router-based inter-VLAN routing, centralized DHCP/DNS, and ACL-based access control between departments.

## What I Did
- Built a 3-department topology (Admin, Sales, HR) connected through a central router
- Configured static IP addressing per department subnet (192.168.10.x, 192.168.20.x, 192.168.30.x)
- Deployed a DHCP + DNS server for the Admin department
- Configured `ip helper-address` to relay DHCP requests across subnets
- Wrote and applied an extended ACL (`HR-ACL`) to block HR-to-Admin traffic while permitting HR-to-Sales and all other traffic
- Verified enforcement with controlled ping tests: Sales → Admin succeeds (0% loss); HR → Admin fails as designed (100% loss, "Destination host unreachable")

## Key Skills
Network Design · Routing · ACL Configuration · DHCP/DNS · Verification Testing

## Evidence
1. [Network Topology Diagram](Figure4-topology.png)
2. [Successful Ping — Sales to Admin](Figure1-ping-success.png)
3. [Failed Ping — HR to Admin (ACL enforced)](Figure2-ping-blocked.png)
4. [Router ACL Configuration & Verification](Figure3-acl-config.png)
5. [Full Project Write-Up (PDF)](Cisco-Packet-Tracer-Network-Configuration-Project.pdf)
