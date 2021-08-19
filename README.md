![awesome azure netapp files](awesomeanf.png?raw=true "Awesome Azure NetApp Files")

# Awesome Azure NetApp Files (ANF) - A curated list of Azure NetApp Files Resources

## General

- [What's new in Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new)
- [Azure NetApp Files Documentation](https://docs.microsoft.com/en-us/azure/azure-netapp-files/)
- [Azure NetApp Files Solution Architectures](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures)
- [SLA for Azure NetApp Files (99.99%)](https://azure.microsoft.com/en-us/support/legal/sla/netapp)
- [Azure NetApp Files Performance and Cost Calculator](https://anftechteam.github.io/calc/)
- [Azure NetApp Files Interactive Region Map](https://anftechteam.github.io/map/)

### Blogs

- [ANFCommunity.com](https://anfcommunity.com)
- [seanluce.com](https://seanluce.com)
- [kirkryan.co.uk](https://kirkryan.co.uk/)

### How-to / Guides

- [Deploying Azure NetApp Files Volumes in Linux - Part 1 [video]](https://www.youtube.com/watch?v=PsupgqUNSA0)
- [Deploying Azure NetApp Files Volumes in Linux - Part 2 [video]](https://www.youtube.com/watch?v=XYXWVyfi25k)
- [Persistent Mounts with Azure NetApp Files (NFS) [video]](https://www.youtube.com/watch?v=KXP87RXokzY)

### Architecture

- [Service Levels](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-service-levels)
- [Resource Limits](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits)

#### Networking

- [Guidelines for Azure NetApp Files network planning](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies)

## Workloads / Use Cases

- [Azure NetApp Files Solution Architectures](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures)

### SAP

- [Architectural Decisions to Maximize ANF Investment for SAP HANA - Part 1](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/architectural-decisions-to-maximize-anf-investment-in-hana-n-m/ba-p/2078737)
- [Azure NetApp Files HANA Certification](https://azure.microsoft.com/en-us/updates/azure-netapp-files-hana-certification-and-new-region-availability/)
- [Deploy SAP HANA Scale-out on Azure VMs with ANF, SLES [docs]](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/sap-hana-scale-out-standby-netapp-files-suse)
- [Deploy SAP HANA Scale-out on Azure VMs with ANF, RHEL [docs]](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/sap-hana-scale-out-standby-netapp-files-rhel)
- [High availability for SAP NetWeaver on Azure VMs with ANF, SLES [docs]](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/high-availability-guide-suse-netapp-files)
- [SAP on Azure - Video Podcast Episode #14 - The One with AN](https://www.youtube.com/watch?v=zPALOig4CRM)
- [SAP on Azure - Video Podcast Episide #15 - The One with ANF, Backup](https://www.youtube.com/watch?v=MvEzYu41Mko)
- [SAP on Azure - Video Podcast Episode #16 - The One with ANF, Recovery & Cloning](https://www.youtube.com/watch?v=oL0ICzfJAfk)

### HPC

- [High Performance Computing on Azure [blog]](https://anfcommunity.com/2020/12/04/high-performance-computing-on-azure/)

### Azure Virtual Desktop

- [Benefits of using Azure NetApp Files with AVD [docs]](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-windows-virtual-desktop)

### Kubernetes / Containers

- [Azure NetApp Files + Astra Trident = Dynamic and Persistent Storage for AKS](https://anfcommunity.com/2021/02/16/azure-netapp-files-trident-dynamic-and-persistent-storage-for-kubernetes/)
- [Azure NetApp files + Astra Trident Integration - Part 2](https://anfcommunity.com/2021/08/01/azure-netapp-files-trident-integration-part-2/)
- [Astra Trident Documentation](https://netapp-trident.readthedocs.io/en/latest/)

### Oracle

- [Oracle Databases on Microsoft Azure [Technical Report]](https://www.netapp.com/pdf.html?item=/media/17105-tr4780pdf.pdf)
- [Oracle on Azure VM Images with Azure NetApp Files [MS Docs]](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/oracle/oracle-vm-solutions#shared-storage-configuration-options)

### SQL Server

- [Deploy SQL Server over SMB with Azure NetApp Files [video]](https://www.youtube.com/watch?v=x7udfcYbibs)
- [Deploy SQL Server Always On Availability Groups with Azure NetApp Files [video]](https://www.youtube.com/watch?v=y3VQmzzeyvc)

## Monitoring / Alerting / Reporting

- [ANFCapacityManager: Automated Alerts and Capacity Management](https://github.com/ANFTechTeam/ANFCapacityManager/blob/master/README.md)
- [ANFHealthCheck: A PowerShell Script to generate beautiful HTML reports](https://github.com/seanluce/ANFHealthCheck)
- [Azure Monitor: How to set up ANF alerts [video]](https://www.youtube.com/watch?v=JUmiSvMSTA0)

## Automation

- [Azure NeAutApp Files Code samples] (https://docs.microsoft.com/en-us/samples/browse/?terms=netapp)
- [Automate Azure NetApp Files with Powershell] (https://anfcommunity.com/2020/09/11/automate-azure-netapp-files-with-powershell/)

### Logic Apps

- [ANFCapacityManager]()
- [Azure NetApp Files Snapshot Scheduler Logic App](https://github.com/ANFTechTeam/anfScheduler)

### Terraform

- [Deploying Azure NetApp Files using Terraform [video]](https://www.youtube.com/watch?v=JrcTXk7_QYI)
- [Terraform: azurerm_netapp_account [docs]](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/netapp_account)
- [Terraform: azurerm_netapp_pool [docs]](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/netapp_pool)
- [Terraform: azurerm_netapp_volume [docs]](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/netapp_volume)
- [Terraform: azurerm_netapp_snapshot [docs]](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/netapp_snapshot)

### Ansible

- [Ansible Modules for Azure NetApp Files](https://galaxy.ansible.com/netapp/azure)

### PowerShell

- [Az.NetAppFiles [docs]](https://docs.microsoft.com/en-us/powershell/module/az.netappfiles)
- [Azure NetApp Files: PowerShell One-Liners](https://anfcommunity.com/2021/08/03/azure-netapp-files-powershell-one-liners/)
- [ANFHealthCheck: A PowerShell Script to generate beautiful HTML reports](https://github.com/seanluce/ANFHealthCheck)

### Azure CLI (az cli)

- [az netappfiles](https://docs.microsoft.com/en-us/cli/azure/netappfiles?view=azure-cli-latest)

### Azure REST API

- [Develop for Azure NetApp Files with REST API [docs]](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-develop-with-rest-api)
- [ANF API 101 with Postman - Part 1](https://anfcommunity.com/2021/02/16/part-1-anf-api-101-with-postman/)
- [ANF API 101 with Postman - PArt 2](https://anfcommunity.com/2021/04/29/part-2-anf-api-101-with-postman/)

## Performance

- [Azure NetApp Files - Performance 101 [video]](https://www.youtube.com/watch?v=mKNcucOtjsU)

## Uncategorized

