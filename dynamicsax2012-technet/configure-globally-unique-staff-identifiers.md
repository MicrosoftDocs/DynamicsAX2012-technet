---
title: Configure globally unique staff identifiers
TOCTitle: Configure globally unique staff identifiers
ms:assetid: c64f1acc-bff8-4e69-a27f-6d76e1b4b68e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733499(v=AX.60)
ms:contentKeyID: 49685460
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure globally unique staff identifiers [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Staff identifiers in Retail installations of Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 R3 are shared globally across companies. Therefore, when you upgrade an installation of Microsoft Dynamics AX 2009 for Retail that has multiple companies, you must assign a globally unique identifier to each staff member.

Additionally, because Microsoft Dynamics AX 2012 R2 and R3 support data partitioning, globally shared staff identifiers can exist only for companies that are contained in a single data partition. If you have multiple partitions that contain multiple companies, you must perform the following procedure separately on each partition. For more information about data partitions, see [Plan for data partitioning](plan-for-data-partitioning.md).


> [!NOTE]
> <P>Administrators who configure staff IDs should use a consistent numbering scheme that complies with the retailer’s business requirements. We recommend that you use fully numeric IDs and passwords, because they make data entry on a touch screen easier.</P>



Use the following procedure to map old staff identifiers to new identifiers.

1.  Click the **Configure globally unique staff identifiers** task in the checklist to open the form that has the same name.

2.  Microsoft Dynamics AX 2012 R2 and R3 only: In the **Partition key** field, select a data partition.

3.  The grid in the form displays a list of staff members and their associated companies in the source system. Use the **New staff ID** field to assign a globally unique ID to each staff member.

4.  Use the **Password** field to assign a password to each staff ID that you created.

5.  Click **Ready for upgrade**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

