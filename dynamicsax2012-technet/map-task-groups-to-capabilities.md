---
title: Map task groups to capabilities
TOCTitle: Map task groups to capabilities
ms:assetid: a8e2f50e-1a6b-4c2c-a0cc-0d584d4b81bf
ms:mtpsurl: https://technet.microsoft.com/library/Gg731889(v=AX.60)
ms:contentKeyID: 35132799
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- capabilities
- map task groups
- task groups
---

# Map task groups to capabilities 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this item on the preprocessing checklist to specify the capability that you must have in order to convert task groups during the upgrade process. Task groups are not available in the target system.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## Update task groups to capabilities

1.  On the **Preprocessing upgrade checklist**, click **Prepare application data for preprocessing** \> **Task group upgrade**

2.  In the **Partition key** field, select a partition for preprocessing.

3.  Select a task group, and then click the **Map task groups** button and choose one of the following conversion methods:

<!-- end list -->

  - To map a task group conversion manually, select the task group and then enter a unique identifier in the **Capability** field for each task group.

  - To automate the mapping and use the task group ID as the identifier for the capability, click the **Map task groups** button and select **Map task groups by task group ID across all company accounts**.

  - To automate the mapping using a 1:1 relationship between task groups and capabilities, click the **Map task groups** button and select **Map task groups 1:1**.


> [!NOTE]
> <P>To delete existing mapping information, click the <STRONG>Map task groups</STRONG> button and select <STRONG>Clear mapping of all task groups</STRONG>.</P>



## See also

[Task group upgrade (form)](https://technet.microsoft.com/library/hh202103\(v=ax.60\))

  


