### Network resiliency

- Configure the switching layer
  - PC1 and PC2 should be in VLAN 10 (access)
  - FW1 and FW2 should be in VLAN 10 (access)
  - SW1 - SW2 the port in between is a trunk (allow vlan 10 only)
- On firewall configure interface
  - towards SW1 / SW2 configure a VRRP group to provide a resilient gateway
  - create two point to points with SW3
    - 10.10.30.0/30
    - 10.10.30.4/30
- Implement OSPF dynamic routing protocol between FW1, FW2 and SW3
- Configure and advertise the subnet between PC3 and SW3
- Test connection between PC1 and PC3, and PC2 and PC3? What do you observe
- What can go wrong?
