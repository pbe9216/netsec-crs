### Site to Site VPN and BGP

Configure a site to site VPN

- Configure addressing on PC and switches, this time the switch will be the gateway on each side using a vlan interface (SVI)
  - csw1 vlan 10 : 10.110.0.0/24
  - csw2 vlan 10 : 192.168.1.0/24
- Configure a point to point routed interface towards the VPN gateway.
  - csw1 - vpn1 : 10.100.0.0/30
  - csw2 - vpn2 : 10.100.0.4/30
  - vpn1 - vpn2 : 8.8.8.0/30
- Configure a loopback interface on each switch
  - csw1 11.11.11.11/32
  - csw2 22.22.22.22/32
- Configure an IPsec VPN between vpn1 and vpn2
  - include vlan 10 subnets and loopbacks in the encryption domain
- Configure an eBGP multihop session between csw1 and csw2 through the VPN tunnel
  - fix the routing
  - advertise vlan 10 subnet using BGP
  - redistribute connected

