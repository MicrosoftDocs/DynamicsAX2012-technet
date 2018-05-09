---
title: Compare data upgrade row counts
TOCTitle: Compare data upgrade row counts
ms:assetid: cc3a5b18-388e-45c0-8681-c057e18cae55
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731949(v=AX.60)
ms:contentKeyID: 35132884
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- count
- compare
- table
- row
- validation
---

# Compare data upgrade row counts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Compare data upgrade row counts** task in the **Data upgrade checklist** checks the data integrity on the Microsoft Dynamics AX 2012 target system following upgrade. Correctly correlated row counts among the source, shadow, and target tables suggest, but do not confirm, that bulk copy and data upgrade finished successfully.


> [!WARNING]
> <P>Row counts are only a preliminary check of data integrity. It is vital to perform more granular checks on data integrity before putting your Microsoft Dynamics AX 2012 system into production.</P>



## Compare source and target row counts

The **Compare data upgrade row counts** form displays related tables as records in a grid. It also provides status figures that report possible problems. At a glance, you can compare table row counts across the upgrade process starting with the source tables, passing to the shadow tables, and ending with the target tables.

Row count is strictly a check on *likely* success or failure of a table upgrade. When counts fail to match, you should investigate the table involved and the script that processed it. However, even a successful match does not guarantee that the upgrade was successful, and a failed match may not correspond to a problem. To be confident that the upgrade succeeded, you must perform validation tailored to your particular business data.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

