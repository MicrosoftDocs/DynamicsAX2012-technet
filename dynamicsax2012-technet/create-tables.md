---
title: Create tables
TOCTitle: Create tables
ms:assetid: c7f84356-e67a-4eea-95fa-5824b05315d0
ms:mtpsurl: https://technet.microsoft.com/library/Gg731932(v=AX.60)
ms:contentKeyID: 35132864
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- tables
- upgrade
---

# Create tables 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You perform the **Create tables** task to prepare the Microsoft Dynamics AX 2012 target database for upgrade. During this step, the Microsoft Dynamics AX 2012 database schema is created based on Application Object Tree (AOT) definitions, including tables, unique clustered indexes, default constraints, and views. (In previous releases of Microsoft Dynamics AX, the database schema was created during the synchronization step.) Other indexes and check constraints are created on tables after bulk copy but before the post-synchronization scripts run.

This task only creates the target database schema; no data is copied from the source system at this time.


> [!IMPORTANT]
> <P>Before you begin this task, use the Microsoft Dynamics AX Server Configuration Utility to confirm that the AOS statement cache is set to 40.</P>
> <OL>
> <LI>
> <P>Click <STRONG>Start</STRONG> &gt; <STRONG>Administrative Tools</STRONG> &gt; <STRONG>Microsoft Dynamics AX &lt;version&gt; Server Configuration Utility</STRONG> &gt; <STRONG>Database Tuning</STRONG>.</P>
> <LI>
> <P>Locate the <STRONG>Statement cache</STRONG> field. Adjust the value if needed.</P>
> <LI>
> <P>Click <STRONG>OK</STRONG>.</P></LI></OL>



Create the target database schema as follows:

1.  In the **Data upgrade checklist**, click **Create tables**.
    
    The **Synchronize table** form displays a progress bar that indicates the status of the operation while the upgrade framework queries the AOT and determines what tables, fields, and indexes to create in the target database. This process may take several minutes to finish.

2.  When the query process is finished, the **Synchronize database** form opens. Information that was collected during the previous step is displayed on four tabs. You can select items to view details about them.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Tab</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Overview</strong></p></td>
    <td><p>Shows what tables need to be created in the target database and summarizes the detailed results provided on the other tabs.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Errors</strong></p></td>
    <td><p>Lists errors that occurred while determining what tables to create. You must fix any errors before you proceed with creating tables.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Warnings</strong></p></td>
    <td><p>Lists all warnings about possible data conflicts that may arise after tables are created. You should review the warnings and decide which of them require developer action.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Info</strong></p></td>
    <td><p>Lists all the tables that will be created in the target database.</p></td>
    </tr>
    </tbody>
    </table>
    
    Address any errors or warnings before you continue with the data upgrade. Unresolved table errors will cause the data upgrade to fail. After you verify that there are no errors or warnings, click **Continue** on the **Synchronize database** form. The upgrade framework creates the tables in the target database.

  


