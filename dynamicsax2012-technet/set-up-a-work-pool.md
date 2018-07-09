---
title: Set up a work pool
TOCTitle: Set up a work pool
ms:assetid: c28b6fe8-2444-45be-ace3-e96a59a706c7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553199(v=AX.60)
ms:contentKeyID: 62200152
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSWorkPool
- MsDynAx060.Forms.WHSWorkPool
- work pool
---

# Set up a work pool [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



You can use work pools to organize work into groups. For example, you can create a work pool to classify work that occurs in a particular warehouse location. For all work types except counting, you can assign a work pool to a work template. For cycle counting, you can assign a work pool to the following:

  - Cycle count plans

  - Cycle count threshold

  - Cycle count work by location

  - Cycle count work by item

When you use work templates to create work, the work pool is automatically assigned to the work. You can also manually assign work pools to work using the **Location directives** form. After a warehouse worker defines the menu items that will be used to perform work on a mobile device, the worker can scan the work pool ID. The work that is related to the work pool ID is then automatically assigned to the work user on the mobile device until all work is completed.

1.  Click **Warehouse management** \> **Setup** \> **Work** \> **Work pools**.

2.  Click **New** to create a work pool.

3.  Enter a unique identifier (ID) and a short description for the work pool.

## Related tasks

[Create a work template](create-a-work-template.md)

[Set up cycle counting thresholds and plans to perform cycle counting](set-up-cycle-counting-thresholds-and-plans-to-perform-cycle-counting.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

