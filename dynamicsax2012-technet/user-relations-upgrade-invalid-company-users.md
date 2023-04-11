---
title: User relations upgrade - invalid company users
TOCTitle: User relations upgrade - invalid company users
ms:assetid: 9c83c299-55c8-47b6-847a-5d39ab64c9b8
ms:mtpsurl: https://technet.microsoft.com/library/Gg731878(v=AX.60)
ms:contentKeyID: 35132781
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# User relations upgrade - invalid company users 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Users can be internal or external. Internal users include employees, and external users include vendors, customers, and prospects. After you specify user relations, a user's information, such as the employee ID or customer account ID, is automatically displayed in fields when that user opens a page in Enterprise Portal for Microsoft Dynamics AX. For external relations, data in the self-service portal for vendors is trimmed according to the user’s designated account. For example, if a user has an external relation for vendor account 1003, the user sees data only for that account in the self-service portal for vendors.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

Use the following procedure to delete user accounts for a company when the user ID is not valid.

## Delete records when a user account has a an invalid ID

1.  Click **User relations upgrade – invalid company users**.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  Click **Delete all**.

4.  Click **Set to ready for upgrade**.

## See also

[User relations upgrade duplicate user IDs](user-relations-upgrade-duplicate-user-ids.md)

  


