## Firewalling (45 min)

Same topology as in lab 1, here we will configure the stateful firewall.

- Each interface should be put in a zone
   - zone blue : VRF blue
   - zone red : VRF red
   - zone green : VLAN 30
- Configure IPs on each interfaces
- Configure the gateway for VLAN 30
- Create a rule that allows ICMP from any to any
- Create a rule that allows TCP 22 from VLAN 20 to 10.1.1.1/32
- Observe traffic flow using firewall tools
- Create a UDP listener with netcat on PC2
- Create a run to allow PC3 to PC2 UDP traffic on the port fixed in the netcat command
- Generate UDP traffic and observe traffic flow in the firewall
- Create a NAT from PC3 to loopback 10.1.1.1/32. PC3 should be SNAT'd to 10.2.2.2/32.
- Observe traffic flow in the firewall. Run a TCPDUMP on SW2 to see what is coming to loopback 10.1.1.1.
