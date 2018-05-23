# Appendix A: IP Addressing Planning Tables

Use the following tables to plan your IP addresses for your on-premises network, Microsoft Azure and your ExpressRoute peerings.

Virtual Network
Always reserve /16 or /18 CIDR blocks for address space while creating the VNET to have enough IP range. VNET address space can be increased later if we are running out of the space
 
On-Premises
Subnet	IP Subnet	Resources	Gateway/Next Hop
 Infrastructure		 	 
Business/App Tier	 	 	 
Data Tier	 	 	 
Active Directory Services	 	 	 
 
Azure: 
Subnet	IP Subnet	Resources	Gateway/Next Hop
GatewaySubnet	 /26 subnet	N/A	N/A
Infrastructure	 1.2	 	 
Business/App Tier	 	 	 
Data Tier	 	 	 
Active Directory Services	 	 	 
 
ExpressRoute Peerings:   
Description 	Peering Assignments	Range Size Required	ASN
Peering:	 	 	 
Private Peering 	Primary 	/30	peer ASN: 
	Secondary 		VLAN ID: 
Public/Microsoft Peering 	Primary 	/30 	Peer ASN: 
	Secondary 		VLAN ID: 

