## Basic device hardening

- Configure a VLAN 10, an SVI with IP 10.10.0.1/24 and access port towards the PC in this VLAN
- Scan the SVI IP, what can we conclude?
- Probe switch through LLDP, what can you find out? 
- Configure LLDP adequately and retry (after TTL expired)?
- Try banner grabbing on open ports, what do you see?
- Configure management interface and management VRF
- Lock down administration services
- Show the default control plane policies and ACLs
- Configure session timeouts
- Enable NTP (for production, NTP should be authenticated)
- Enable logging
- Configure local account and password encryption
