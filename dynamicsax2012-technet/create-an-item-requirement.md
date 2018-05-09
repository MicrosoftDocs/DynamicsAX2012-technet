---
title: Create an item requirement
TOCTitle: Create an item requirement
ms:assetid: 629262ef-dff7-4290-9c5d-9d788146056a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500664(v=AX.60)
ms:contentKeyID: 37822144
ms.date: 06/07/2014
mtps_version: v=AX.60
f1_keywords:
- project
- sales order
- item requirement
---

# Create an item requirement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to create an item requirement for a project. Item requirement transactions are included in a sales order. Although a sales order is processed when the corresponding customer invoice is updated, item requirements are processed when the corresponding packing slip is updated. All item requirement lines for a project are maintained in a single sales order, even if other lines in the **Sales order** form have been processed.


> [!NOTE]
> <P>When an item is reserved as an item requirement for a project, the order type of the resulting sales order is <STRONG>Item requirements</STRONG>. For information about sales order types, see <A href="about-sales-order-types.md">About sales order types</A>.</P>



To create an item requirement for a project, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select or open a project.

3.  Depending on the version of Microsoft Dynamics AX you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: On the **Action Pane**, on the **Plan** tab, in the **Item requirements** group, click **Item requirements**.
    
      - In earlier versions of AX 2012: On the **Action Pane**, on the **Manage** tab, in the **New** group, click **Item task**, and then click **Item requirement**.

4.  In the **Item requirements** form, click **New** to create a new line.

5.  Define the requirement.

After you create an item requirement, the item or items can be consumed from the current inventory if at least one of the following conditions is true:

  - The item was picked from the current inventory.

  - The item can be purchased through a purchase order.

  - The item can be created through a production order.

For information about the consumption of item requirements, see [Consume item requirements in a project](consume-item-requirements-in-a-project.md).

## See also

[Item requirements (form)](https://technet.microsoft.com/en-us/library/aa552021\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

