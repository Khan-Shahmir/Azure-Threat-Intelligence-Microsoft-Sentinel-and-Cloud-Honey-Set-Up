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

Private Endpoint for Azure Storage allows you to securely access Azure Storage services over a private connection within an Azure Virtual Network (VNet). This integration ensures that traffic between your VNet and Azure Storage remains within the Azure network, enhancing security and compliance. By assigning a private IP address to Azure Storage services, it minimizes exposure to the public internet and reduces the attack surface. With Private Endpoint, applications and services within the same VNet can access Azure Storage securely without the need for public endpoints, ensuring data privacy and confidentiality.

12) 






![Monitor For Windows](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/f9630ec1-8318-4041-a035-9d165bb09551)


Windows Server on Log Analytics Workspace in Microsoft Azure integrates Windows Server with Azure's Log Analytics service, providing comprehensive monitoring, management, and analytics capabilities. This integration enables the collection and analysis of logs, performance data, and system events from Windows Servers deployed in Azure or on-premises. By connecting Windows Servers to a Log Analytics Workspace, you gain insights into system health, security, and performance metrics in near real-time.

13) 






![Monitor For Linux](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/1c4fb361-d990-48a3-a394-0e6010ab213e)


Linux Server on Log Analytics Workspace in Microsoft Azure integrates Linux-based servers with Azure's Log Analytics service, offering extensive monitoring, management, and analytics capabilities. This integration allows the collection and analysis of logs, performance data, and system events from Linux servers deployed in Azure or on-premises. By connecting Linux servers to a Log Analytics Workspace, administrators gain insights into system health, security, and performance metrics in near real-time. These insights aid in troubleshooting, proactive monitoring, and generating reports to enhance operational efficiency and ensure compliance. 

14) 







![Data Collection Rules](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/5dd68c06-d65a-45d3-abe1-3f3108f8e99b)

Data Collection Rules (DCRs) in Microsoft Azure are configurations that define what data is collected from various sources and how it is processed. These rules are part of Azure Monitor and are used to gather telemetry data from different Azure and non-Azure sources such as virtual machines, applications, and services. DCRs specify which types of logs, metrics, or traces to collect, where to send the data, and how to process it. They allow customization of data collection based on specific requirements and preferences. Once configured, DCRs enable monitoring, analysis, and visualization of data, providing insights into system performance, health, and security.

15) 






![Data Sources DCR](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/0744b298-aa98-47c4-8b4f-db46dd98db1d)

Data sources in Microsoft Azure include Azure services like Virtual Machines, Azure SQL Database, and Azure Storage, as well as non-Azure resources such as on-premises servers, applications, and third-party services. These sources emit telemetry data, including logs, metrics, and traces, which Azure Monitor collects for monitoring and analysis. By aggregating data from diverse sources, Azure enables comprehensive insights into the performance, health, and security of cloud and hybrid environments.

16) 






![Windows Event Logs](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/9649b017-04e4-4080-becd-ab7ec582d967)

Windows Event Logs in Microsoft Azure provide critical insights into system performance, security, and operational health. Azure services like Azure Monitor, Azure Security Center, and Azure Sentinel collect and analyze these logs to monitor resource performance, detect security threats, and respond to incidents. Through centralized logging and analysis, Azure offers a comprehensive solution for monitoring Windows Event Logs across various Azure resources. Additionally, custom log collection and analysis enable users to gain deeper insights into their applications and tailor monitoring to specific needs.

17) 






![LAW Windows Event Log - Custom](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/bc2c1f0e-6788-457f-926f-b47311acc74b)

Windows Event Logs custom-form in Microsoft Azure enables tailored monitoring and analysis of specific events within applications and systems. Azure allows users to define and collect custom event logs based on unique requirements. These logs can include application-specific events, operational metrics, or business-related activities. Leveraging Azure Log Analytics, users can query and analyze these custom logs to gain insights into application performance, troubleshoot issues, and optimize operations efficiently. With customizable event log collection, Azure provides a flexible solution for monitoring and managing diverse Azure environments.

18)






![Linux Syslog](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/c87d6ceb-1186-4318-910f-a1740b22aa07)

Linux syslog in Microsoft Azure offers a centralized logging solution for monitoring and analyzing system events and activities. Azure services like Azure Monitor and Azure Log Analytics collect syslog data from Linux-based resources. This data includes system logs, application logs, and custom logs, providing insights into system performance, security incidents, and operational issues. By aggregating syslog data, Azure enables efficient troubleshooting, proactive monitoring, and compliance reporting for Linux environments. Leveraging Azure's scalable infrastructure, users can easily manage and analyze syslog data, ensuring the reliability and security of their Linux-based systems in the Azure cloud.

19) 






![Incident](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/ad7390a5-294b-4122-a9ee-b8699d223a71)


Incidents on Microsoft Azure refer to unexpected events or disruptions that impact the availability, performance, or security of Azure services or resources. These incidents can range from service outages to security breaches or performance degradation. Microsoft Azure provides robust incident management processes to detect, respond to, and mitigate these incidents promptly. Through Azure Service Health and Azure Status, users receive real-time updates on incidents, including their severity, impact, and resolution status. 

20)





![IP Brute Force](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/a438f711-674d-47b7-b15d-c88f7f44a2d5)


Custom brute force attempt Linux syslog on Microsoft Azure signifies unauthorized login attempts using repeated, automated login guesses. Azure's syslog collection gathers these events, providing visibility into potential security threats. By analyzing these logs, Azure Security Center and Azure Sentinel can detect patterns indicative of brute force attacks, such as multiple failed login attempts within a short period. These incidents trigger alerts, allowing security teams to respond swiftly to mitigate risks and strengthen security measures. 

21) 






![Sentinel Analytics](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/30425bd5-55ca-4eba-b66c-e58a8e51ec42)

Microsoft Sentinel Analytics is a powerful security information and event management (SIEM) solution offered by Microsoft. It provides advanced threat detection, investigation, and response capabilities across the entire IT environment. Sentinel Analytics leverages AI and machine learning to detect anomalies, suspicious activities, and security threats in real-time. It aggregates and analyzes data from various sources, including logs, telemetry, and threat intelligence feeds. Security analysts can use Sentinel Analytics to investigate incidents, correlate data, and identify the root cause of security events. 

23) 






![Sentinel Fusion Rule](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/5ffc5dd5-2feb-4af6-bc5f-5e9683b5c6d7)


Microsoft Sentinel Fusion Rules are a key feature in Azure Sentinel that enable advanced threat detection by combining multiple detection logics and data sources. These rules integrate signals from various security products and sources, enhancing detection accuracy and reducing false positives. Fusion Rules use machine learning algorithms to analyze correlated data and identify complex attack patterns. They allow security analysts to create customized detection rules tailored to their organization's specific security requirements. By consolidating multiple detection logics into a single rule, Fusion Rules streamline the detection process and provide more comprehensive threat detection capabilities. Overall, Fusion Rules in Microsoft Sentinel empower organizations to strengthen their security posture and respond effectively to emerging threats.

24) 







![Watchlist](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/210842dc-32a1-41e2-a4cf-656da36206de)

In Microsoft Azure, a watchlist is a feature in Azure Sentinel that allows security teams to create and manage lists of entities such as IP addresses, URLs, or file hashes that they want to monitor for security-related activities. These lists can include known malicious entities, trusted assets, or entities specific to the organization's environment. Azure Sentinel can use these watchlists to enrich security analysis and threat detection by comparing incoming data against the entities in the watchlist. When a match is found, Azure Sentinel can trigger alerts or take automated response actions, helping security teams identify and respond to threats more effectively. Watchlists provide a flexible way to tailor threat detection and response to the unique needs of each organization.

25) 





![Linux SSH Threat Workbook](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/d398fa02-23b1-47b5-83ff-ff6e417e5b2b)

26) 







![MSSQL Threat Workbook](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/37326790-2cf5-41da-8838-9dfede296de7)

27) 






![NSG Malicious Threat Workbook](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/d3b1d052-9a4f-48e1-bd1e-1c1782d018b7)

28) 






![Windows RDP Threat Workbook](https://github.com/Khan-Shahmir/Azure-Threat-Intelligence-Microsoft-Sentinel-and-Cloud-Honey-Set-Up/assets/143667443/d811d942-955e-4d1a-83e3-8ed9ffd3ab94)




