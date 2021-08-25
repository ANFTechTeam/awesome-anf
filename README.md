![awesome azure netapp files](awesomeanf.png?raw=true "Awesome Azure NetApp Files")

# Awesome Azure NetApp Files (ANF) - A curated list of Azure NetApp Files Resources

- [Awesome Azure NetApp Files (ANF) - A curated list of Azure NetApp Files Resources](#awesome-azure-netapp-files-anf---a-curated-list-of-azure-netapp-files-resources)
  - [General](#general)
    - [Blogs](#blogs)
    - [How-to / Guides](#how-to--guides)
    - [Architecture](#architecture)
      - [Networking](#networking)
  - [Workloads / Use Cases](#workloads--use-cases)
    - [SAP](#sap)
    - [HPC](#hpc)
    - [Azure Virtual Desktop](#azure-virtual-desktop)
    - [Kubernetes / Containers](#kubernetes--containers)
    - [Oracle](#oracle)
    - [SQL Server](#sql-server)
  - [Monitoring / Alerting / Reporting](#monitoring--alerting--reporting)
  - [Automation](#automation)
    - [Logic Apps](#logic-apps)
    - [Terraform](#terraform)
    - [Ansible](#ansible)
    - [PowerShell](#powershell)
    - [Azure CLI (az cli)](#azure-cli-az-cli)
    - [Azure REST API](#azure-rest-api)
  - [Performance](#performance)
    - [Performance Information](#performance-information)
    - [Performance Reference for Azure NetApp Files](#performance-reference-for-azure-netapp-files)
  - [Data Protection](#data-protection)
    - [Snapshots](#snapshots)
    - [Cross-Region Replication (CRR)](#cross-region-replication-crr)
  - [Troubleshooting](#troubleshooting)
  - [Other](#other)

## General

- [What's new in Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new)
- [Azure NetApp Files Documentation](https://docs.microsoft.com/en-us/azure/azure-netapp-files/)
- [Azure NetApp Files Solution Architectures](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures)
- [SLA for Azure NetApp Files (99.99%)](https://azure.microsoft.com/en-us/support/legal/sla/netapp)
- [Azure NetApp Files Performance and Cost Calculator](https://anftechteam.github.io/calc/)
- [Azure NetApp Files Interactive Region Map](https://anftechteam.github.io/map/)
- [FAQs about Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs#networking-faqs)
- [Cost model for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-cost-model)

### Blogs

- [ANFCommunity.com](https://anfcommunity.com)
- [seanluce.com](https://seanluce.com)
- [kirkryan.co.uk](https://kirkryan.co.uk/)

### How-to / Guides

- [Deploying Azure NetApp Files Volumes in Linux - Part 1 [video]](https://www.youtube.com/watch?v=PsupgqUNSA0)
- [Deploying Azure NetApp Files Volumes in Linux - Part 2 [video]](https://www.youtube.com/watch?v=XYXWVyfi25k)
- [Persistent Mounts with Azure NetApp Files (NFS) [video]](https://www.youtube.com/watch?v=KXP87RXokzY)
- [Migrate to Azure NetApp Files](https://anfcommunity.com/2021/04/28/migrating-to-azure-netapp-files/)
- [Quickstart: Set up Azure NetApp Files and create an NFS volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-quickstart-set-up-account-create-volumes?tabs=azure-portal)
- [Create an NFS volume for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes)
- [How to do SMB on Azure NetApp Files](https://anfcommunity.com/2020/09/18/how-to-do-smb-on-anf/)
- [Create an SMB volume for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes-smb#control-access-to-an-smb-volume)
- [Create a dual-protocol volume for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-volumes-dual-protocol)

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
- [What is Azure Application Consistent Snapshot tool (AzAcSnap)](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-introduction)
- [SAP HANA disaster recovery with Azure NetApp Files [Technical Report]](https://docs.netapp.com/us-en/netapp-solutions-sap/backup/saphana-dr-anf_data_protection_overview_overview.html)

### HPC

- [High Performance Computing on Azure [blog]](https://anfcommunity.com/2020/12/04/high-performance-computing-on-azure/)
- [Choose the best service level of Azure NetApp Files for your HPC applications](https://docs.microsoft.com/en-us/learn/modules/choose-service-level-azure-netapp-files-hpc-applications/)
- [Improve Azure NetApp Files performance for your EDA and HPC applications by using best practices](https://docs.microsoft.com/en-us/learn/modules/improve-azure-netapp-files-performance-hpc-eda-best-practices/)
- [Run high-performance computing (HPC) applications on Azure](https://docs.microsoft.com/en-us/learn/paths/run-high-performance-computing-applications-azure/)

### Azure Virtual Desktop

- [Benefits of using Azure NetApp Files with AVD [docs]](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-windows-virtual-desktop)

### Kubernetes / Containers

- [Azure NetApp Files + Astra Trident = Dynamic and Persistent Storage for AKS](https://anfcommunity.com/2021/02/16/azure-netapp-files-trident-dynamic-and-persistent-storage-for-kubernetes/)
- [Azure NetApp files + Astra Trident Integration - Part 2](https://anfcommunity.com/2021/08/01/azure-netapp-files-trident-integration-part-2/)
- [Astra Trident Documentation](https://netapp-trident.readthedocs.io/en/latest/)

### Oracle

- [Oracle Databases on Microsoft Azure [Technical Report]](https://www.netapp.com/pdf.html?item=/media/17105-tr4780pdf.pdf)
- [Oracle on Azure VM Images with Azure NetApp Files [MS Docs]](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/oracle/oracle-vm-solutions#shared-storage-configuration-options)
- [Benefits of using Azure NetApp Files with Oracle Database](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-benefits-azure-netapp-files-oracle-database)

### SQL Server

- [Deploy SQL Server over SMB with Azure NetApp Files [video]](https://www.youtube.com/watch?v=x7udfcYbibs)
- [Deploy SQL Server Always On Availability Groups with Azure NetApp Files [video]](https://www.youtube.com/watch?v=y3VQmzzeyvc)
- [Benefits of using Azure NetApp Files for SQL Server deployment](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-benefits-azure-netapp-files-sql-server)
- [SQL Server on Azure deploymnet guide using Azure NetApp Files](https://www.netapp.com/pdf.html?item=/media/27154-tr-4888.pdf)

## Monitoring / Alerting / Reporting

- [ANFCapacityManager: Automated Alerts and Capacity Management](https://github.com/ANFTechTeam/ANFCapacityManager/blob/master/README.md)
- [ANFHealthCheck: A PowerShell Script to generate beautiful HTML reports](https://github.com/seanluce/ANFHealthCheck)
- [Azure Monitor: How to set up ANF alerts [video]](https://www.youtube.com/watch?v=JUmiSvMSTA0)

## Automation

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
- [Automate Azure NetApp Files with Powershell](https://anfcommunity.com/2020/09/11/automate-azure-netapp-files-with-powershell/)

### Azure CLI (az cli)

- [az netappfiles](https://docs.microsoft.com/en-us/cli/azure/netappfiles?view=azure-cli-latest)
- [Azure NetApp Files Code samples](https://docs.microsoft.com/en-us/samples/browse/?terms=netapp)


### Azure REST API

- [Develop for Azure NetApp Files with REST API [docs]](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-develop-with-rest-api)
- [ANF API 101 with Postman - Part 1](https://anfcommunity.com/2021/02/16/part-1-anf-api-101-with-postman/)
- [ANF API 101 with Postman - PArt 2](https://anfcommunity.com/2021/04/29/part-2-anf-api-101-with-postman/)

## Performance

### Performance Information

- [Azure NetApp Files - Performance 101 [video]](https://www.youtube.com/watch?v=mKNcucOtjsU)
- [Performance considerations for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-performance-considerations)
- [Performance benchmark test recommendations for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-performance-metrics-volumes)
- [Azure NetApp Files performance benchmarks for Linux](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-benchmarks-linux)
- [Performance impact of Kerberos on Azure NetApp Files NFSv4.1 volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-impact-kerberos)
- [Oracle database performance on Azure NetApp Files single volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-oracle-single-volumes)

### Performance Reference for Azure NetApp Files

- [Linux direct I/O best practices for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-direct-io)
- [Linux filesystem cache best practices for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-filesystem-cache)
- [Linux NFS mount options best practices for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-mount-options)
- [Linux concurrency best practices for Azure NetApp Files - Session slots and slot table entries](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-concurrency-session-slots)
- [Linux NFS read-ahead best practices for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-nfs-read-ahead)
- [SMB performance best practices for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-smb-performance)
- [Azure virtual machine SKUs best practices for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-virtual-machine-sku)


## Data Protection

### Snapshots

- [How Azure NetApp Files Snapshots work](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-introduction)
- [Manage Snapshots by using Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-manage-snapshots)

### Cross-Region Replication (CRR)

- [Manage Disaster Recovery using Cross-Region Replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-manage-disaster-recovery)
- [Create volume replication for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-create-peering)
- [Display health status of replication relationship](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-display-health-status)
- [Delete volume replication or volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-delete)

## Troubleshooting

- [Troubleshoot Capacity Pools](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-capacity-pools)
- [Troubleshoot Cross-Region Replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-cross-region-replication)
- [Troubleshoot SMB or dual-protocol volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-dual-protocol-volumes)
- [Troubleshoot NFSv4.1 kerberos volume issues](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-nfsv41-kerberos-volumes)
- [Troubleshoot snapshot policies](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-snapshot-policies)
- [Troubleshoot LDAP volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-ldap-volumes)
- [Troubleshoot Resource Provider errors](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-troubleshoot-resource-provider-errors)

## Other

- [Storage service add-ons for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/storage-service-add-ons)
- [Using Azure Policy with Azure NetApp Files](https://anfcommunity.com/2021/04/19/azure-policy-now-available-for-azure-netapp-files/)
