## Layer 2 security (60 min)

### CAM tables
- Explore MAC address table size
  - Look for Arista datacenter switch table size: https://www.arista.com/assets/data/pdf/Whitepapers/Arista_7280_Switch_Architecture.pdf
  - Look for a lower end campus switch from Cisco: https://www.cisco.com/c/en/us/products/collateral/switches/catalyst-9200-series-switches/nb-06-cat9200-ser-data-sheet-cte-en.html
- Test a MAC flooding attack on a switch
- Verify at the same time the mac address count
- What happens when a switch MAC table is full?
- Implement a security to prevent MAC flooding

### Rogue DHCP
- Configure R1 interface eth1
- Configure DHCP server
- Try to run a real DHCP request
- Perform a DHCP starvation attack (yersinia)
- Observe effect and switch
- Observe effect on router

### Neighbor discovery
- Look for neighboring information
- What can you find out?
