ANF documentation activities for August 2021:

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
