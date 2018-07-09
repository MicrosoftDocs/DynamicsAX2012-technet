---
title: Presynchronize (upgrade)
TOCTitle: Presynchronize (upgrade)
ms:assetid: 44585f2f-9b9e-4155-8288-a48e93ef0a82
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731786(v=AX.60)
ms:contentKeyID: 35132617
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- database
- data
---

# Presynchronize (upgrade) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you perform the **Presynchronize** task in the target system, you use the **Data upgrade cockpit (%1 -\> %2)** to run scripts that map the database schema on the source Microsoft Dynamics AX system to the database schema on the target system. This table-to-table and column-to-column mapping is new with Microsoft Dynamics AX 2012, and prepares the target database for synchronization. If like-to-like mapping fails and errors result, you can manually repair the mapping and rerun the script.

Indexing is disabled while the presynchronization scripts are running.

The presynchronization scripts that ship with Microsoft Dynamics AX 2012 are meant to serve as models for developers of new Microsoft Dynamics AX modules.

Prepare your database for synchronization as follows:

1.  In the **Data upgrade checklist**, click **Presynchronize**. The **Data upgrade cockpit (%1 -\> %2)** opens and lists the upgrade tasks to be completed.

2.  Click **Run**. In the **Upgrade job** grid, an icon next to each job indicates the job’s status as the presynchronization scripts run.

3.  Address any errors that occur and then rerun the scripts.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

