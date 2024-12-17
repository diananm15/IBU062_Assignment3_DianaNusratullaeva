All devices in the Network

 Router:

  FastEthernet0/0: 168.90.0.1 (assigned 168.90.0.0 network)
  FastEthernet1/0: 210.3.14.1 (assigned to 210.3.14.0 network)

Switch 1:
  PC0: IP Address - 168.90.0.3 
  PC1: IP Address - 168.90.0.4 
  Laptop1: IP Address - 168.90.0.5 
  Server1: IP Address - 168.90.0.6

 Switch 2:
  Server2: IP Address - 210.3.14.4
  Server0: IP Address - 210.3.14.2 
  PC2: IP Address - 210.3.14.3 

 IP Address Scheme

 Network 0 (168.90.0.0/16): Devices connected to Switch 1
 Default Gateway: 168.90.0.1 (Router)

 Network 1 (210.3.14.0/24): Devices connected to Switch 2
 Default Gateway: 210.3.14.1 (Router)


Updates to the network configuration

New PC:
Two new PCs have been added to the network:
One PC is connected to -Switch 1
One PC is connected to -Switch 2
These PCs are configured to automatically obtain IP addresses via - DHCP.

Switch 1:
  PC0: IP Address - 168.90.0.3 
  PC1: IP Address - 168.90.0.4 
  PC3: IP Address - 168.90.0.2 
  Laptop1: IP Address - 168.90.0.5 
  Server1: IP Address - 168.90.0.6

 Switch 2:
  Server2: IP Address - 210.3.14.4
  Server0: IP Address - 210.3.14.2 
  PC2: IP Address - 210.3.14.3
  PC4: IP Address - 210.3.14.5

