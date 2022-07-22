<ins>Azure Bastion</ins> - Directly exposing RDP(port 3389) to outside Vnet can be riskly and can invite Ransomeware attacks. To Protect this Azure provides a 
service called Azure Bastion. <br/>					
For creating Azure Bastion we need to create a separate subnet named as AzurreBastionSubnet with a ip prefix of at least /27. <br/>
