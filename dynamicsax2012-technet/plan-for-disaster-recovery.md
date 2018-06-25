---
title: Plan for disaster recovery
TOCTitle: Plan for disaster recovery
ms:assetid: 9c2b4440-c706-4899-b1d0-f550979ae319
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn433225(v=AX.60)
ms:contentKeyID: 56561978
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Plan for disaster recovery [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To guarantee that all your systems and data can be quickly restored to regular operation if a disaster occurs through natural or human causes, you must implement a comprehensive disaster recovery plan. As you create this plan, consider the various kinds of disasters that might affect your organization. These disasters might include natural disasters, such as a fire, and technical disasters, such as a multi-disk failure in a RAID. When you create a disaster recovery plan, identify the steps that are required to respond to each kind of disaster. You must test the recovery steps for each scenario. We recommend that you verify the robustness of your disaster recovery plan by simulating a catastrophic event.

When you plan for disaster recovery, consider your specific environmental and business needs. For example, if a fire occurs and wipes out your 24-hour data center, are you sure that you can recover? If you can recover, how long does it take you to recover and make your system available? How much data loss can your users tolerate?

We recommend that your disaster recovery plan specify how long recovery should take and the final database state that users can expect. For example, you may determine that recovery can be completed in 48 hours after replacement hardware is acquired, and that data can be guaranteed only until the end of the previous week.

A disaster recovery plan can be structured in various ways and can contain many kinds of information. A comprehensive recovery plan contains the following elements:

  - A plan to acquire hardware, or to create and share virtual servers in another location.

  - A communication plan.

  - A list of people who must be contacted if a disaster occurs.

  - Instructions for contacting the people who are involved in the response to the disaster.

  - Information about who will administer the plan.

  - A checklist of the tasks that are required for each recovery scenario. To help you review the disaster recovery later, initial each task on the checklist as it is completed, and indicate the time that the task was completed.

To guarantee that you are ready for disaster, we recommend that you periodically perform the following actions:

  - Perform regular backups of databases, transaction logs, and file systems to minimize the amount of data that is lost. We recommend that you back up both system databases and user databases.

  - Test your backup and recovery procedures thoroughly. You must perform appropriate testing to make sure that you have the backups that are required to recover from various failures, and that the backups function correctly. Testing also helps you make sure that your procedures are clearly defined and documented, and that they can be executed smoothly and quickly by any qualified operator.

  - Maintain system logs in a secure manner. Keep records of all service packs that have been installed for Microsoft Windows, your database, and Microsoft Dynamics AX.

  - On another server or set of servers, test the steps that are required to recover from a disaster. If necessary, modify the steps so that they are appropriate to the server environment, and then test the modified steps.

  - Make sure that you understand and document the database rights that are required to recover the database.

  - Plan for the loss of your whole infrastructure and each Microsoft Dynamics AX server component. Additionally, consider the effect if the domain controller for your Microsoft Dynamics AX implementation is lost.

  - Make sure that you identify all employees who perform recovery tasks. Additionally, make sure that you document all tasks that are required, so that the tasks can be performed even if those specific employees are unavailable.

## Choose a database protection method

The methods for protecting databases for disaster recovery are similar to the methods used to ensure database availability. The following table lists options.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Option</p></th>
<th><p>Pros</p></th>
<th><p>Cons</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Database mirroring</p></td>
<td><p>Fast failover, consistent when &quot;high safety&quot; mode is used.</p>
<p>Almost real time</p>
<p>Servers can be geographically dispersed</p></td>
<td><p>Mirrored datas is not accessible</p>
<p>Dual commit in &quot;high safety&quot; mode require SQL Server Enterprise Edition</p></td>
</tr>
<tr class="even">
<td><p>Log shipping</p></td>
<td><p>Relatively easy to set up</p>
<p>Stable</p></td>
<td><p>Data is only as consistent as the last transaction log applied</p>
<p>Log shipped database is not accessible</p></td>
</tr>
<tr class="odd">
<td><p>One way transactional replication</p></td>
<td><p>Almost real time</p></td>
<td><p>Difficult to configure with Microsoft Dynamics AX</p>
<p>Difficult to determine which transactions were committed and which were rolled back at failover</p></td>
</tr>
<tr class="even">
<td><p>AlwaysOn availability groups</p></td>
<td><p>Fast failover</p>
<p>Consistent</p>
<p>Less overhead than mirroring</p>
<p>Readable secondaries</p>
<p>Multiple secondaries</p>
<p>Can be geographically dispersed</p></td>
<td><p>Requires SQL Server Enterprise Edition</p></td>
</tr>
<tr class="odd">
<td><p>Database backups</p></td>
<td><p></p></td>
<td><p>Time to restore, migrate to a new environment</p></td>
</tr>
<tr class="even">
<td><p>SAN replication</p></td>
<td><p>Robust</p>
<p>Almost real time</p>
<p>Consistent</p>
<p>Can be geographically dispersed</p></td>
<td><p>Expensive</p>
<p>Difficult to configure</p></td>
</tr>
<tr class="odd">
<td><p>Virtual environment snapshots</p></td>
<td><p>Easy to restore</p></td>
<td><p>Requires that you run virtual environments</p>
<p>Only as consistent as last snapshot saved</p></td>
</tr>
</tbody>
</table>


## Next steps

For more information about how to implement a disaster recovery strategy for your environment, see the following documentation:

  - [Back up and recover databases (SQL Server)](back-up-and-recover-databases-sql-server.md)

  - [Backing Up and Restoring Databases in SQL Server](http://go.microsoft.com/fwlink/?linkid=215815)

  - [High Availability and Disaster Recovery for SharePoint Server 2010](http://go.microsoft.com/fwlink/?linkid=215820)

  - [Backup and Restore Operations for a Reporting Services Installation](http://go.microsoft.com/fwlink/?linkid=215818)

  - [Managing Backing Up and Restoring (Analysis Services)](http://go.microsoft.com/fwlink/?linkid=215819)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

