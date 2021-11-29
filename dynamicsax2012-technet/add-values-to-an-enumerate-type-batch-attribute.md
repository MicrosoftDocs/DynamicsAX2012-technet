---
title: Add values to an enumerate type batch attribute
TOCTitle: Add values to an enumerate type batch attribute
ms:assetid: ed57628a-5194-457e-9da1-f239d1bfcbcc
ms:mtpsurl: https://technet.microsoft.com/library/Hh227500(v=AX.60)
ms:contentKeyID: 36059904
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add values to an enumerate type batch attribute 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to add values to an enumerate type batch attribute. Enumerate values follow a particular sequence or pattern. For example, an attribute you define as Color might have enumerate values of Green, Yellow, Blue, and Red.

1.  Click **Inventory management** \> **Setup** \> **Batch attributes** \> **Batch attributes**.

2.  Select a batch attribute of the attribute type **Enumerate**.

3.  Click the **Attribute enumerate values** button. The **Attribute enumerate values** form is displayed.

4.  Press CTRL+N to add a new line.

5.  In the **Sequence** field, enter the sequence in which the new enumerate value should display.
    

    > [!NOTE]
    > <P>Once you assign an enumerate attribute type to an inventory batch, you cannot change its sequence value until all inventory batches that use it are either deleted or archived, or the batch attribute itself is changed or reset. If you predict a sequence change based on future needs, use a number sequence that includes breaks in the numbering pattern. For example, instead of using the sequence 1, 2, 3, you might use 10, 20, 30.</P>



6.  In the **Attribute enumerate value** field, enter the value for the attribute.

## See also

[About batch attributes](about-batch-attributes.md)

[Attribute enumerate values (form)](https://technet.microsoft.com/library/hh208618\(v=ax.60\))

[Batch attributes (form)](https://technet.microsoft.com/library/hh209255\(v=ax.60\))

  


