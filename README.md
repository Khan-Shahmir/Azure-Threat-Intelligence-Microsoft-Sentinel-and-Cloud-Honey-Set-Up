# Project-Azure-Threat-Intelligence


Introduction to Project Azure Threat Intelligence


In the world of cloud, security remains a top priority, especially when using powerful platforms like Microsoft Azure. The Azure Threat Intelligence project aims to utilize Azure's extensive security tools to detect, analyze, and counter threats efficiently. This effort involves implementing various security measures across different Azure components, including Storage Accounts, Virtual Networks, and Key Vaults. The objective is to create a secure cloud infrastructure that can withstand cyber threats and adhere to industry regulations. Here are the list of screenshots I captured while conducting the project and will present the meaning behind them. 


1)    







![CreatedKeyVault](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/c9f436b6-23de-46c2-b50a-f5d76714da66)

 A private endpoint for Azure Key Vault is a network interface that connects you privately and securely to the Key Vault service using a private IP address from your virtual network. This eliminates exposure to the public internet and reduces the attack surface. When you create a private endpoint, the connection must be approved. If the resource for which you're creating a private endpoint is in your directory, you'll be able to approve the connection request provided you have sufficient permissions. The private endpoint uses a private IP address in your virtual network, and you can connect to an instance of an Azure resource.
 
2) 






![CreatedPrivateStorage](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/1c79e04f-bd63-460d-9ca8-2f12341e523c)

Private Endpoint for Azure Storage allows you to securely connect your Azure Storage accounts to your virtual network, providing a private IP address within that network. This private IP address can then be used to access Azure Storage resources without exposure to the public internet. Private Endpoint for Azure Storage supports various services, including Blob Storage, Azure Files, Azure Queues, and Azure Tables. This means you can use Private Endpoint for a wide range of storage-related tasks. Each Private Endpoint is assigned a private IP address within your virtual network. This allows applications and services within the same virtual network to securely access Azure Storage using this private IP, keeping the traffic isolated. You can create Private Endpoints in one or more virtual networks to integrate with Azure Storage accounts. This integration is seamless and ensures secure connectivity between your Azure resources and storage.

3) 






![EastUs](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/2024e154-ad6a-4e15-902b-b40bbfe752b1)

Network Watcher Topology on Microsoft Azure is an interactive interface that allows you to visualize and manage your cloud network infrastructure. It provides a graphical representation of resources and their relationships across multiple subscriptions, regions, and resource groups. With Topology, you can diagnose and troubleshoot network issues by gaining contextual access to Network Watcher diagnostic tools such as connection troubleshoot, packet capture, and next hop.

4) 







![SOC Subnet](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/4b1a86a1-53b5-4cf4-a4f1-2e852a2ba372)

A virtual network (VNet) in Microsoft Azure is an isolated network environment where Azure resources can securely communicate. It allows you to create a private space in the Azure cloud, similar to a traditional network in an on-premises data center. Within a VNet, you can define IP address ranges, subnets, and routing tables to control traffic flow and network access. Virtual machines, Azure App Services, and other Azure resources can be deployed within a VNet, enabling them to communicate with each other securely.

5) 







![Perimeter Firewall(External)](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/12accbb5-49a9-4cca-8f0e-4aa1ac51d58c)

Azure's perimeter firewall is a crucial security component for virtual networks, controlling inbound and outbound traffic. It allows you to define rules based on source and destination IP addresses, ports, and protocols to enforce security policies. With stateful inspection, it monitors the state of connections to make informed decisions on allowing or blocking traffic. Integrated with Azure Security Center, it provides logging, monitoring, and threat detection capabilities, ensuring continuous protection of your Azure environment.

6) 






![ExternalFirewallProtectingSoc1](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/2e5b7704-e587-4900-b016-1e97d3f24fef)

An external firewall in a Microsoft Azure virtual network is a security measure that helps protect cloud networks, on-premises or physical datacenter networks, and the internet. It is typically implemented as a part of a perimeter network, which is a secure subnet that incoming packets flow through before reaching back-end servers. Azure provides several features and services for implementing external firewalls

7) 







![WindowsVM-IP](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/e16231bd-5c0f-4754-9066-53f34937bcbf)


A Windows virtual machine (VM) on Microsoft Azure provides a scalable and flexible environment for running Windows-based applications and services in the cloud. It allows you to deploy Windows Server or Windows client operating systems on Azure infrastructure.

8) 






![LinuxVM-IP](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/7a81f848-b80a-486f-9b10-0152581523cd)

A Linux virtual machine (VM) on Microsoft Azure is a scalable and secure computing resource that can be created, configured, and managed in the Azure portal. It is deployed within a virtual network and can be assigned a public IP address for internet connectivity. The Azure Linux Agent (waagent) provides various configuration options for customizing the VM's behavior.

9) 






![QualysVM-IP](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/5ae6e1a5-092d-4549-a13b-785a0f1f82e9)


Qualys Virtual Machine for Microsoft Azure is a cloud-based solution designed to continuously assess the security posture of Azure virtual machines (VMs). It automates vulnerability management by identifying, prioritizing, and remediating security vulnerabilities in VMs. The Qualys solution integrates seamlessly with Azure, providing comprehensive visibility into VM security across the Azure environment. It offers continuous monitoring, real-time alerts, and detailed reports to help organizations stay compliant with security standards and regulations. With Qualys Virtual Machine, Azure users can proactively secure their cloud infrastructure, reduce security risks, and maintain a strong security posture.

10) 






![PrivateEndpointKeyVault](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/f32a8eea-aa68-4db4-935d-75de4b062f84)

Private Endpoint for Azure Key Vault allows you to securely access Key Vault over a private connection within your Azure Virtual Network (VNet). This integration enhances security by keeping traffic within the Azure network, mitigating exposure to the public internet. It enables you to access Key Vault resources such as keys, secrets, and certificates securely from VMs and other Azure services within the same VNet. Private Endpoint provides a private IP address for Key Vault, enhancing isolation and reducing the attack surface. This setup ensures that sensitive data stored in Key Vault remains protected and compliant with regulatory requirements.

11) 






![PrivateEndpointStorage](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/1d876710-35ab-487b-96c0-65aa79664a78)

12) 






![Monitor For Windows](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/f9630ec1-8318-4041-a035-9d165bb09551)

13) 






![Monitor For Linux](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/1c4fb361-d990-48a3-a394-0e6010ab213e)

14) 






![Data Collection Rules](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/5dd68c06-d65a-45d3-abe1-3f3108f8e99b)

15) 






![Data Sources DCR](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/0744b298-aa98-47c4-8b4f-db46dd98db1d)

16) 






![Windows Event Logs](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/9649b017-04e4-4080-becd-ab7ec582d967)

17) 






![LAW Windows Event Log - Custom](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/bc2c1f0e-6788-457f-926f-b47311acc74b)

18)






![Linux Syslog](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/c87d6ceb-1186-4318-910f-a1740b22aa07)

19) 






![Incident](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/ad7390a5-294b-4122-a9ee-b8699d223a71)

20)






![Linux Syslog](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/60c9ea3f-5216-4552-8a22-5b460c228e17)

21) 






![IP Brute Force](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/a438f711-674d-47b7-b15d-c88f7f44a2d5)

22) 






![Sentinel Analytics](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/30425bd5-55ca-4eba-b66c-e58a8e51ec42)

23) 






![Sentinel Fusion Rule](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/5ffc5dd5-2feb-4af6-bc5f-5e9683b5c6d7)

24) 







![Watchlist](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/210842dc-32a1-41e2-a4cf-656da36206de)

25) 





![Linux SSH Threat Workbook](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/d398fa02-23b1-47b5-83ff-ff6e417e5b2b)

26) 







![MSSQL Threat Workbook](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/37326790-2cf5-41da-8838-9dfede296de7)

27) 






![NSG Malicious Threat Workbook](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/d3b1d052-9a4f-48e1-bd1e-1c1782d018b7)

28) 






![Windows RDP Threat Workbook](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/d811d942-955e-4d1a-83e3-8ed9ffd3ab94)




