---
title: Select which employee number to upgrade
TOCTitle: Select which employee number to upgrade
ms:assetid: 6eb262c8-9c53-44c7-919a-e9100c1c1256
ms:mtpsurl: https://technet.microsoft.com/library/Gg188983(v=AX.60)
ms:contentKeyID: 35410563
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Select which employee number to upgrade 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you used virtual companies in Microsoft Dynamics AX 2009, you might have two or more employee records that are associated with the same Address book ID (partyId). Microsoft Dynamics AX 2012 does not support having employee records that share the same Address book ID (partyId). Before you upgrade to Microsoft Dynamics AX 2012, for each set of employee records that share the same Address book ID (partyId), you must select one of the employee records to upgrade.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## Select which employee records to upgrade

1.  In the **Preprocessing upgrade checklist**, expand the **Prepare application data for preprocessing** node and then select **Select which employee number to upgrade**.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  In the **Select which employee number to upgrade** form, a list of employee records is displayed. This list contains sets of records that share the same Address book ID (partyId). To indicate which records should be upgraded, select the **Selected** check box for only one record in each set of records that share the same Address book ID (partyId).

4.  Click **View related data loss** to open the **Data loss for discarded EmplIds** form, where you can view the data associated with the records that you did not select in step 2. This data will not be upgraded.

5.  Click **Close** to return to the **Select which employee number to upgrade** form.

6.  Click **Ready for upgrade**.

## See also

[Select which employee number to upgrade (form)](https://technet.microsoft.com/library/hh202069\(v=ax.60\))

[Data loss for discarded EmplIds (form)](https://technet.microsoft.com/library/hh202102\(v=ax.60\))

  


