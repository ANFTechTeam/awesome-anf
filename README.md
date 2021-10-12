![awesome azure netapp files](awesomeanf.png?raw=true "Awesome Azure NetApp Files")

# Awesome Azure NetApp Files (ANF) - A curated list of Azure NetApp Files Resources

- [Awesome Azure NetApp Files (ANF) - A curated list of Azure NetApp Files Resources](#awesome-azure-netapp-files-anf---a-curated-list-of-azure-netapp-files-resources)
  - [General](#general)
    - [Training](#training)
    - [Blogs](#blogs)
    - [How-to / Guides](#how-to--guides)
      - [Manage NFS volumes](#manage-nfs-volumes)
      - [Manage SMB volumes](#manage-smb-volumes)
      - [Manage dual-protocol volumes](#manage-dual-protocol-volumes)
      - [Manage volume access and encryption](#manage-volume-access-and-encryption)
      - [Mount or unmount a volume](#mount-or-unmount-a-volume)
      - [Manage volume capacity and performance](#manage-volume-capacity-and-performance)
    - [Architecture](#architecture)
      - [Networking](#networking)
  - [Workloads / Use Cases](#workloads--use-cases)
    - [SAP](#sap)
    - [HPC](#hpc)
    - [SAS](#sas)
    - [Azure Virtual Desktop](#azure-virtual-desktop)
    - [Citrix](#citrix)
    - [Kubernetes / Containers](#kubernetes--containers)
    - [Azure Red Hat Openshift](#azure-red-hat-openshift)
    - [Azure Batch](#azure-batch)
    - [Oracle](#oracle)
    - [SQL Server](#sql-server)
    - [Azure VMware Solution](#azure-vmware-solution)
    - [Machine Learning](#machine-learning)
    - [Education](#education) 
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
    - [Backup](#backup)
  - [Troubleshooting](#troubleshooting)
  - [Other](#other)

## General

- [What's new in Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new)
- [ANF Documentation Changes, updated September 2021](ANF-Doc-Updates.md)
- [Azure NetApp Files Documentation](https://docs.microsoft.com/en-us/azure/azure-netapp-files/)
- [Azure NetApp Files Solution Architectures](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures)
- [SLA for Azure NetApp Files (99.99%)](https://azure.microsoft.com/en-us/support/legal/sla/netapp)
- [Azure NetApp Files Performance and Cost Calculator](https://anftechteam.github.io/calc/)
- [Azure NetApp Files Interactive Region Map](https://anftechteam.github.io/map/)
- [FAQs about Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs)
- [Cost model for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-cost-model)

### Training

- [Introduction to Azure NetApp Files](https://docs.microsoft.com/en-us/learn/modules/introduction-to-azure-netapp-files/)
- [Choose the best service level of Azure NetApp Files for your HPC applications](https://docs.microsoft.com/en-us/learn/modules/choose-service-level-azure-netapp-files-hpc-applications/)
- [Improve Azure NetApp Files performance for your EDA and HPC applications by using best practices](https://docs.microsoft.com/en-us/learn/modules/improve-azure-netapp-files-performance-hpc-eda-best-practices/)
- [Run high-performance computing (HPC) applications on Azure](https://docs.microsoft.com/en-us/learn/paths/run-high-performance-computing-applications-azure/)

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

#### Manage NFS volumes

- [Create an NFS volume for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes)
- [Configure NFSv4.1 default domain](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-configure-nfsv41-domain)
- [Configure NFSv4.1 Kerberos encrpyption](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-kerberos-encryption)
- [Configure ADDS LDAP with extended groups for NFS](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-ldap-extended-groups)
- [Configure an NFS client for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-nfs-clients)

#### Manage SMB volumes

- [How to do SMB on Azure NetApp Files](https://anfcommunity.com/2020/09/18/how-to-do-smb-on-anf/)
- [Create an SMB volume for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes-smb)
- [Enable Continuous Availability on existing SMB volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/enable-continuous-availability-existing-smb)

#### Manage dual-protocol volumes

- [Create a dual-protocol volume for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-volumes-dual-protocol)

#### Manage volume access and encryption

- [Configure Export policy for NFS or dual protocol](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-configure-export-policy)
- [Configure Unix permissions and change ownership mode](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-unix-permissions-change-ownership-mode)

#### Mount or unmount a volume

- [Mount or unmount a volume for Windows or Linux virtual machines](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-mount-unmount-volumes-for-virtual-machines)

#### Manage volume capacity and performance

- [Monitor the capacity of a volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/monitor-volume-capacity)
- [Resize a capacity pool or volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resize-capacity-pools-or-volumes)
- [Dynamically change the service level of a volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/dynamic-change-volume-service-level)

### Architecture

- [Service Levels](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-service-levels)
- [Resource Limits](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits)

#### Networking

- [Guidelines for Azure NetApp Files network planning](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies)

## Workloads / Use Cases

- [Azure NetApp Files Solution Architectures](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures)

### SAP

- [Designing SAP Global transport directory using ANF in Azure](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/designing-sap-global-transport-directory-using-anf-in-azure/ba-p/2621547)
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
- [Azure NetApp Files: Getting the most out of your cloud storage](https://cloud.netapp.com/hubfs/Resources/ANF%20PERFORMANCE%20TESTING%20IN%20TEMPLATE.pdf)
- [Run MPI workloads with Azure Batch and Azure NetApp Files](https://azure.microsoft.com/en-us/resources/run-mpi-workloads-with-azure-batch-and-azure-netapp-files/)
- [Azure Cycle Cloud: CycleCloud HPC environments on Azure NetApp Files](https://docs.microsoft.com/en-us/azure/cyclecloud/overview?view=cyclecloud-8)
- [High Performance computing (HPC): Oil and gas in Azure](https://techcommunity.microsoft.com/t5/azure-global/high-performance-computing-hpc-oil-and-gas-in-azure/ba-p/824926)
- [Run reservoir simulation software on Azure](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/infrastructure/reservoir-simulation)
- [Benefits of using Azure NetApp Files for electronic design automation](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-benefits-azure-netapp-files-electronic-design-automation)
- [Azure CycleCloud: EDA HPC Lab with Azure NetApp Files](https://github.com/Azure/cyclecloud-hands-on-labs/blob/master/EDA/README.md)
- [Azure for the semiconductor industry](https://azurecomcdn.azureedge.net/cvt-f40f39cd9de2d875ab0c198a8d7b186350cf0bca161e80d7896941389685d012/mediahandler/files/resourcefiles/azure-for-the-semiconductor-industry/Azure_for_the_Semiconductor_Industry.pdf)

### SAS

- [Azure NetApp Files: A Shared file system to use with SAS Grid on Microsoft Azure](https://communities.sas.com/t5/Administration-and-Deployment/Azure-NetApp-Files-A-shared-file-system-to-use-with-SAS-Grid-on/m-p/705192)
- [Azure NetApp Files: A Shared file system to use with SAS Grid on MS Azure - RHEL8.3/nconnect UPDATE](https://communities.sas.com/t5/Administration-and-Deployment/Azure-NetApp-Files-A-shared-file-system-to-use-with-SAS-Grid-on/m-p/722261#M21648)
- [Best Practices for Using Microsoft Azure with SAS](https://communities.sas.com/t5/Administration-and-Deployment/Best-Practices-for-Using-Microsoft-Azure-with-SAS/m-p/676833#M19680)
- [SAS on Azure architecture guide - Azure Architecture Center | Azure NetApp Files](https://docs.microsoft.com/en-us/azure/architecture/guide/sas/sas-overview#azure-netapp-files-nfs)

### Azure Virtual Desktop

- [Benefits of using Azure NetApp Files with AVD [docs]](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-windows-virtual-desktop)
- [Storage options for FSLogix profile containers in Azure Virtual Desktop](https://docs.microsoft.com/en-us/azure/virtual-desktop/store-fslogix-profile#azure-platform-details)
- [Create an FSLogix profile container for a host pool using Azure NetApp Files](https://docs.microsoft.com/en-us/azure/virtual-desktop/create-fslogix-profile-container)
- [Azure Virtual Desktop at Enterprise Scale](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/wvd/windows-virtual-desktop)
- [Microsoft FSLogix for the enterprise - Azure NetApp Files best practices](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/wvd/windows-virtual-desktop-fslogix#azure-netapp-files-best-practices)
- [Setting up Azure NetApp Files for MSIX App Attach](https://techcommunity.microsoft.com/t5/azure-virtual-desktop/setting-up-azure-netapp-files-for-msix-app-attach-step-by-step/m-p/1990021)

### Citrix

- [Citrix Profile Management with Azure NetApp Files Best Practices Guide](https://www.netapp.com/pdf.html?item=/media/55973-tr-4901.pdf)

### Kubernetes / Containers

- [Azure NetApp Files + Astra Trident = Dynamic and Persistent Storage for AKS](https://anfcommunity.com/2021/02/16/azure-netapp-files-trident-dynamic-and-persistent-storage-for-kubernetes/)
- [Azure NetApp files + Astra Trident Integration - Part 2](https://anfcommunity.com/2021/08/01/azure-netapp-files-trident-integration-part-2/)
- [Astra Trident Documentation](https://netapp-trident.readthedocs.io/en/latest/)
- [Astra: protect, recover, and manage your AKS workloads on Azure NetApp Files](https://cloud.netapp.com/hubfs/Astra%20Azure%20Documentation.pdf)
- [Integrate Azure NetApp Files with Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/azure-netapp-files)
- [Out-of-This-World Kubernetes performance on Azure with Azure NetApp Files](https://cloud.netapp.com/blog/ma-anf-blg-configure-kubernetes-openshift)
- [Trident - Storage Orchestrator for Container](https://netapp-trident.readthedocs.io/en/stable-v20.04/kubernetes/operations/tasks/backends/anf.html)
- [Magneto e-commerce platform in Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/magento/magento-azure)

### Azure Red Hat Openshift

- [Using Trident to Automate Azure NetApp Files from OpenShift](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/using-trident-to-automate-azure-netapp-files-from-openshift/ba-p/2367351)

### Azure Batch

- [Run MPI workloads with Azure Batch and Azure NetApp Files](https://azure.microsoft.com/en-us/resources/run-mpi-workloads-with-azure-batch-and-azure-netapp-files/)

### Oracle

- [Oracle Database with Azure NetApp Files - Azure Example Scenarios](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/file-storage/oracle-azure-netapp-files)
- [Oracle Databases on Microsoft Azure [Technical Report]](https://www.netapp.com/pdf.html?item=/media/17105-tr4780pdf.pdf)
- [Oracle on Azure VM Images with Azure NetApp Files [MS Docs]](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/oracle/oracle-vm-solutions#shared-storage-configuration-options)
- [Benefits of using Azure NetApp Files with Oracle Database](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-benefits-azure-netapp-files-oracle-database)

### SQL Server

- [Deploy SQL Server over SMB with Azure NetApp Files [video]](https://www.youtube.com/watch?v=x7udfcYbibs)
- [Deploy SQL Server Always-On Availability Groups with Azure NetApp Files [video]](https://www.youtube.com/watch?v=y3VQmzzeyvc)
- [Deploy SQL Server Always-On Failover Cluster over SMB with Azure NetApp Files [video]](https://www.youtube.com/watch?v=zuNJ5E07e8Q)
- [Benefits of using Azure NetApp Files for SQL Server deployment](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-benefits-azure-netapp-files-sql-server)
- [SQL Server on Azure deploymnet guide using Azure NetApp Files](https://www.netapp.com/pdf.html?item=/media/27154-tr-4888.pdf)
- [SQL Server on Azure Virtual Machines with Azure NeTapp Files](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/file-storage/sql-server-azure-netapp-files)

### Azure VMware Solution

- [Azure NetApp Files with Azure VMware Solution - Guest OS Mounts](https://docs.microsoft.com/en-us/azure/azure-vmware/netapp-files-with-azure-vmware-solution)

### Machine Learning

- [Cloudera Machine Learning](https://docs.cloudera.com/machine-learning/cloud/requirements-azure/topics/ml-requirements-azure.html)
- [Distributed training in Azure: Lane detection - Solution design](https://docs.netapp.com/us-en/netapp-solutions/ai/runai-ld_executive_summary.html)

### Education

- [Moodle on Azure NetApp Files NFS storage](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-netapp-files-for-nfs-storage-with-moodle/ba-p/2300630)

## Monitoring / Alerting / Reporting

- [ANFCapacityManager: Automated Alerts and Capacity Management](https://github.com/ANFTechTeam/ANFCapacityManager/blob/master/README.md)
- [ANFHealthCheck: A PowerShell Script to generate beautiful HTML reports](https://github.com/seanluce/ANFHealthCheck)
- [Azure Monitor: How to set up ANF alerts [video]](https://www.youtube.com/watch?v=JUmiSvMSTA0)

## Automation

### Logic Apps

- [ANFCapacityManager](https://github.com/ANFTechTeam/ANFCapacityManager)
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
- [How snapshots can be vaulted for long-term retention and cost savings](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-introduction#how-snapshots-can-be-vaulted-for-long-term-retention-and-cost-savings)
- [Create an on-demand snapshot](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-manage-snapshots)
- [Manage snapshot policies](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-manage-policy)
- [Edit the Hide Snapshot Path](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-edit-hide-path)
- [Restore a snapshot to a new volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-restore-new-volume)
- [Restore a file from a snapshot using a client](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-restore-file-client)
- [Restore a volume using snapshot revert](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-revert-volume)
- [Delete snapshots](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-delete)

### Cross-Region Replication (CRR)

- [Understand Cross-region replicaton of Azure NetApp Files volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-introduction)
- [Requirements and considerations for using cross-region replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-requirements-considerations)
- [Manage Disaster Recovery using Cross-Region Replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-manage-disaster-recovery)
- [Create volume replication for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-create-peering)
- [Display health status of replication relationship](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-display-health-status)
- [Delete volume replication or volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-delete)

### Backup

- [Understand Azure NetApp Files backup](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-introduction)
- [Requirements and considerations for Azure NetApp Files backup](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-requirements-considerations)
- [Configure policy-based backups for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-configure-policy-based)
- [Configure manual backups for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-configure-manual)
- [Manage backup policies for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-manage-policies)
- [Search backups of Azure NetApp Files volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-search)
- [Restore a backup to a new volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-restore-new-volume)
- [Disable backup functionality for a volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-disable)
- [Delete backups of a volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-delete)
- [Azure NetApp Files backup FAQs](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs#azure-netapp-files-backup-faqs)

## Troubleshooting

- [Troubleshoot Capacity Pools](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-capacity-pools)
- [Troubleshoot Cross-Region Replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-cross-region-replication)
- [Troubleshoot SMB or dual-protocol volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-dual-protocol-volumes)
- [Troubleshoot NFSv4.1 kerberos volume issues](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-nfsv41-kerberos-volumes)
- [Troubleshoot snapshot policies](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-snapshot-policies)
- [Troubleshoot LDAP volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-ldap-volumes)
- [Troubleshoot Resource Provider errors](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-troubleshoot-resource-provider-errors)

## Other

- [Azure NetApp Files for Azure Government](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-government)
- [Storage service add-ons for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/storage-service-add-ons)
- [Using Azure Policy with Azure NetApp Files](https://anfcommunity.com/2021/04/19/azure-policy-now-available-for-azure-netapp-files/)


