## ANF documentation activities for October 2021:
*   Documentation enhancement - Table of Content restructure
    *   Articles under Concepts are now grouped into subcategories.
    *   The single FAQ article is now split into individual articles according to the subject.
    *   [Regional capacity quota](https://docs.microsoft.com/en-us/azure/azure-netapp-files/regional-capacity-quota) is now a standalone article.
*   \[new feature\] Standard network features
    *   \[new\] [Configure network features for a volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-network-features) - Describes network feature registration and configuration steps.
    *   [Guidelines for Azure NetApp Files network planning](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies) - New and updated subsections:  
    \- \[new\] [Configurable network features](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies#configurable-network-features)   
    \- [Constraints](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies#constraints)  
    \- [Supported network topologies](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies#supported-network-topologies)  
    \- [UDRs and NSGs](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies#udrs-and-nsgs)
    *   [What's new](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new) - Feature announcement.
    *   [Create an NFS volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes), [Create an SMB volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes-smb), [Create a dual-protocol volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-volumes-dual-protocol) – Added a mention about the **Network Features** UI and point to the new article for steps.
    *   [Troubleshoot volume errors](https://docs.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-volumes#errors-for-volume-allocation) \- Error messages related to volume allocation
    *   [Networking FAQs for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/faq-networking) - Removed entry "Does Azure NetApp Files support Network Security Groups?", which indicated NSG isn't supported.
*   The Azure NetApp Files service no longer requires waitlist registration:
    *   [Register for NetApp _**Resource Provider**_](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-register) - Removed Waitlist section; retitled article.
    *   [Quickstart: Set up Azure NetApp Files and NFS volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-quickstart-set-up-account-create-volumes?tabs=azure-portal) - Removed Waitlist requirement
    *   [Create a NetApp account](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-netapp-account) - Removed Waitlist requirement
    *   [What is Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-introduction) - Removed Waitlist requirement
    *   [Troubleshoot Resource Provider errors](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-troubleshoot-resource-provider-errors) - Removed Waitlist requirement
*   [Understand cross-region replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-introduction):
    *   Is now generally available (GA):
        *   Removed waitlist/registration requirement from all relevant articles, incl.:
            *   [Understand cross-region replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-introduction)
            *   [Requirements and considerations for cross-region replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-requirements-considerations)
            *   [Create volume replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-create-peering)
        *   [What’s New](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new) – Announcing GA of cross-region replication.
        *   [Azure NetApp Files for Azure Government](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-government) - Update Cross-region replication status to GA for public cloud.
    *   Added more supported pairs:
        *   Added to [Azure regional pairs](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-introduction#azure-regional-pairs):
            *   Asia-Pacific : East Asia <> Southeast Asia
            *   Switzerland: Switzerland North <> Switzerland West
            *   US Government: US Gov Arizona <> US Gov Texas
        *   Added to [Azure regional non-standard pairs](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-introduction#azure-regional-non-standard-pairs):
            *   US Government: US Gov Arizona <> US Gov Virginia
*   [NFS FAQ](https://docs.microsoft.com/en-us/azure/azure-netapp-files/faq-nfs) - Updated _[_Can I use the same file path (volume creation token) for multiple volumes_](https://docs.microsoft.com/en-us/azure/azure-netapp-files/faq-nfs#can-i-use-the-same-file-path-volume-creation-token-for-multiple-volumes)__._
*   [Enable Continuous Availability on existing SMB volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/enable-continuous-availability-existing-smb) - Added reminder: Continuous Availability should be enabled only for SQL Server and FSLogix user profile containers. 
*   [Configure export policy for NFS or dual protocol](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-configure-export-policy) - Clarified that the Root Access option is not available for NFSv4.1 Kerberos volumes.
*   [Requirements and considerations for Azure NetApp Files backup](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-requirements-considerations) – Added consideration: ANF backup is not supported on a cross-region replication _destination_ volume.
*   [Solution architectures using Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures) -
    *   Subsection [File sharing and Global File Caching](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures#file-sharing-and-global-file-caching)
        *   \[new\] [Disaster Recovery for Enterprise File Shares with Azure NetApp Files and DFS Namespaces](https://techcommunity.microsoft.com/t5/azure-architecture-blog/disaster-recovery-for-enterprise-file-shares/ba-p/2808757)
    *   Subsection [Machine Learning](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures#machine-learning)
        *   \[new\] [Distributed training in Azure: Click-Through Rate Prediction – Solution design](https://docs.netapp.com/us-en/netapp-solutions/ai/aks-anf_introduction.html)
    *   Subsection [Azure Kubernetes Services and Kubernetes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures#azure-kubernetes-services-and-kubernetes)
        *   \[updated\] [Integrate Azure NetApp Files with Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/azure-netapp-files) - Updated with details about how to create ANF volumes to be used by pods in an Azure Kubernetes Service (AKS) cluster by using [Astra Trident](https://docs.netapp.com/us-en/trident/index.html). (Contribution from NetApp AKS team)
## ANF documentation activities for Septempter 2021:
*   \[new feature\] Azure NetApp Files backup
    *   \[new\] [Understand Azure NetApp Files backup](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-introduction)
    *   \[new\] [Requirements and considerations for Azure NetApp Files backup](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-requirements-considerations)
    *   \[new\] [Configure policy-based backups](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-configure-policy-based)
    *   \[new\] [Configure manual backups](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-configure-manual)
    *   \[new\] [Manage backup policies](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-manage-policies)
    *   \[new\] [Search backups](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-search)
    *   \[new\] [Restore a backup to a new volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-restore-new-volume)
    *   \[new\] [Disable backup functionality](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-disable)
    *   \[new\] [Delete backups](https://docs.microsoft.com/en-us/azure/azure-netapp-files/backup-delete)
    *   [What's new](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new) _\-_ Feature announcement.
    *   [How Azure NetApp Files snapshots work](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-introduction) -
        *   \[New subsections\] _[How snapshots can be vaulted for long-term retention and cost savings](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-introduction#how-snapshots-can-be-vaulted-for-long-term-retention-and-cost-savings)_, _[Restoring volume backups from vaulted snapshots](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-introduction#restoring-volume-backups-from-vaulted-snapshots)_, and _[Deleting vaulted snapshots](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-introduction#deleting-vaulted-snapshots)_. 
        *   Updates throughout the article.
    *   [Azure NetApp Files backup FAQs](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs#azure-netapp-files-backup-faqs) - Added backup FAQs.
    *   [Resource limits](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits) \- Added backup resource limits to table.
    *   [Volume backup metrics](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-metrics#volume-backup-metrics) - Added backup metrics
*   \[new\] [Azure NetApp Files for Azure Government](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-government) - Describes Azure NetApp Files feature availability in Azure Government and how to access the Azure NetApp Files service within Azure Government.
*   \[new option\] **Administrators** for Active Directory connections
    *   [Create and manage Active Directory connections](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-active-directory-connections) – Under Step 3 (Protocol), added **Administrators** bullet for the new UI. 
    *   [What's new](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new) – Added introduction about **Administrators**
*   [Resource limits for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits) - Default limit for the number of cross-region replication data protection volumes (destination volumes) has been updated to 10.
*   [Create and manage Active Directory connections](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-active-directory-connections) -- Subsection _[Azure Active Directory Domain Services](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-active-directory-connections#azure-active-directory-domain-services)_ added POSIX attribute consideration about using AADDS with a dual-protocol volume.
*   [Configure an NFS client for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-nfs-clients) - Subsection [_RHEL 8 configuration if you are using dual protocol_](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-nfs-clients#rhel-8-configuration-if-you-are-using-dual-protocol) has updated details about ldap\_id\_mapping and other configurations under Step 3.
*   [Configure ADDS LDAP with extended groups for NFS](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-ldap-extended-groups) –
    *   Updated guidelines about \`objectClass\` values for POSIX attributes.
    *   Clarified that the feature enables access to _files and directories_ in the volume.
*   [Create a dual-protocol volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-volumes-dual-protocol#manage-ldap-posix-attributes) - Updated guidelines about \`objectClass\` values for POSIX attributes.
*   [Enable Continuous Availability on existing SMB volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/enable-continuous-availability-existing-smb) - Step 4 updated for clarity.
    *   [Understand cross-region replication](https://review.docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-introduction) - Restructured tables to list geo(s) by pair and Azure regional pairs added the following:
    *   North Central US and South Central US 
    *   US Gov Virginia and US Gov Texas
*   [Manage disaster recovery](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-manage-disaster-recovery) - Updated subsection _[Resync volumes after disaster recovery](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-manage-disaster-recovery#resync-replication)_ with additional explanation about the resync operation. 
*   [Metrics for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-metrics#replication) – Removed an unsupported metric.
*   Performance articles updated:
    *   [Performance benchmark test recommendations for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-performance-metrics-volumes) – Updated overview.
    *   [Performance benchmarks for Linux](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-benchmarks-linux) – Updated details about the graphs. 
*   [Solution architectures using Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures):
    *   \[new subsection\] _[Azure Red Hat Openshift](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures#azure-red-hat-openshift)_ **-** Added [Using Trident to Automate Azure NetApp Files from OpenShift](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/using-trident-to-automate-azure-netapp-files-from-openshift/ba-p/2367351)
    *   _[SQL Server](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures#sql-server)_ - Added  [SQL Server on Azure Virtual Machines with Azure NetApp Files - Azure Example Scenarios](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/file-storage/sql-server-azure-netapp-files)
    *   _[Oracle](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures#oracle)_ - Added  [Oracle Database with Azure NetApp Files - Azure Example Scenarios](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/file-storage/oracle-azure-netapp-files)
    *   _[SAP HANA](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures#sap-hana)_ - Added  [SAP HANA Disaster Recovery with Azure NetApp Files](https://docs.netapp.com/us-en/netapp-solutions-sap/pdfs/sidebar/SAP_HANA_Disaster_Recovery_with_Azure_NetApp_Files.pdf)
*   [FAQs about Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs) - Added new subsection _[Application resilience FAQs](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs#application-resilience-faqs)_.
*   [Release Notes for AzAcSnap](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-release-notes) - AzAcSnap v5.0.2 is available.
*   Doc enhancements:
    *   Table of content (TOC) restructure: Articles in **How-To Guides** section are further categorized and grouped under sub-nodes.
    *   Split subsections of article _Manage snapshots_ into standalone articles:
        *   [Create an on-demand snapshot](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-manage-snapshots)
        *   [Manage snapshot policies](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-manage-policy)
        *   [Edit the Hide Snapshot Path](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-edit-hide-path)
        *   [Restore a snapshot to a new volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-restore-new-volume)
        *   [Restore a file from a snapshot using a client](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-restore-file-client)
        *   [Restore a volume using snapshot revert](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-revert-volume)
        *   [Delete snapshots](https://docs.microsoft.com/en-us/azure/azure-netapp-files/snapshots-delete)

## ANF documentation activities for August 2021:
* \[**new feature**\] Chown mode export policy support and chmod (Unix permissions)
    * \[new\] [Configure Unix permissions and change ownership mode](https://docs.microsoft.com/en-us/azure/azure-netapp-files/configure-unix-permissions-change-ownership-mode) – Describes setting the **Unix permissions** and the **change ownership mode** (**Chown** **Mode**) options for NFS volumes or dual-protocol volumes with the ‘Unix’ security style.
    * [Configure export policy](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-configure-export-policy) – Added new UI **Chown** **Mode**.
    * [Create an NFS volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes) and [Create a dual-protocol volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-volumes-dual-protocol) – Step 3 (**Protocol** tab) describes new UI **Unix permissions****.**
    * [What's New](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new) \- Feature announcement.
* \[**new feature**\] Dual protocol access for NFSv4.1 and SMB
    * [Create a dual-protocol volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-volumes-dual-protocol) –
        * Updated Security Style details.
        * Step 3 (**Protocol**) added new UI elements **Versions** and **Kerberos**; added AFEC registration for using NFSv4.1 and SMB dual protocol.
    * [Create an NFS volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes), [Create an SMB volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes-smb), [Configure export policy for an NFS volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-configure-export-policy) \- Added "NFSv4.1 and SMB" as supported versions for dual-protocol.
    * [What's new](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new) \- Feature announcement.
* \[**new feature**\] Support for enabling Continuous Availability on existing SMB volumes:
    * \[new\] [Enable Continuous Availability on existing SMB volumes](https://docs.microsoft.com/en-us/azure/azure-netapp-files/enable-continuous-availability-existing-smb) – Describes editing an SMB volume to enable the **Enable Continuous Availability** option.
    * [What's new](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new) – Feature announcement.
    * Removed previously published article “Convert existing SMB volumes to use Continuous Availability” (no longer applicable).
* Snapshot policy is generally available (GA) –
    * [Manage snapshots](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-manage-snapshots) subsection [Manage snapshot policies](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-manage-snapshots#manage-snapshot-policies) – Removed requirements for snapshot policy feature registration.
    * [What's new](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new) – GA announcement.
* [Understand cross-region replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-introduction) –
    * Supported Azure regional pairs now include:
        * UAE North and UAE Central
        * Norway East and Norway West
    * Supported Azure regional non-standard pairs now include:
        * Germany West Central and France Central
* [Resource limits for Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits) \-\- The following subsections of are updated to reflect the Quota blade in portal:
    * [Regional capacity quota](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits#regional-capacity-quota)
    * [Request limit increase](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits#request-limit-increase)
* [FAQs about Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs) \- Added new entry:
    * _[_When I delete an Azure NetApp Files volume, is the data deleted safely?_](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs#when-i-delete-an-azure-netapp-files-volume-is-the-data-deleted-safely)_
* Clarification about SMB share permissions :
    * [Create an SMB volume](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes-smb) \- Removed Share Permissions subsection (no longer applicable).
    * Added FAQ entry _[Can the SMB share permissions be changed?](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-faqs#can-the-smb-share-permissions-be-changed)_
* [Delegate a subnet to Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-delegate-subnet) \- Consideration about the wizard for creating a new subnet is updated with additional details. 
* [Create and manage Active Directory connections](https://docs.microsoft.com/en-us/azure/azure-netapp-files/create-active-directory-connections) –
    * Removed the requirement about _usi_ng Enterprise or Premium SKUs with Azure NetApp Files.
    * Added reminder to update password configured in the Active Directory Connections if you change the password of the Active Directory user account that is used in Azure NetApp Files.
* [Create volume replication](https://docs.microsoft.com/en-us/azure/azure-netapp-files/cross-region-replication-create-peering) \- Added a note that you might see a difference between the used space of the source volume and the used space of the destination volume.
* [Linux concurrency best practices](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-concurrency-session-slots) \- NFSv3 subsections [Example 4](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-concurrency-session-slots#example-4--250-nfs-clients-8-sunrpcmax_tcp_slot_table_entries-and-no-nconnect-for-a-maximum-concurrency-of-2000) and [How to calculate concurrency settings by connection count](https://docs.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-concurrency-session-slots#how-to-calculate-concurrency-settings-by-connection-count) have updated best practices.
* "Windows Virtual Desktop" is now "Azure Virtual Desktop".  The following articles are updated with the name change:
    * [Benefits of using Azure NetApp Files with Azure Virtual Desktop](https://docs.microsoft.com/en-us/azure/azure-netapp-files/solutions-windows-virtual-desktop)
    * [Solution architectures using Azure NetApp Files](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-solution-architectures)
    * [What's new](https://docs.microsoft.com/en-us/azure/azure-netapp-files/whats-new)
