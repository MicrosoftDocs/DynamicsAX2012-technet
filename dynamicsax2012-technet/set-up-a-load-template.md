---
title: Set up a load template
TOCTitle: Set up a load template
ms:assetid: 98200da2-092e-4539-91b6-ddad53c0ab78
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553182(v=AX.60)
ms:contentKeyID: 62200122
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSLoadTemplate
- load template
- load templates
---

# Set up a load template [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



When you create a new load, you can assign a load template that contains information about equipment and measures such as height, width, depth, and volume of the load.

This topic describes how to set up load templates and how to associate a load template with a new load.

## Set up load templates

To set up load templates, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Load template**.

2.  In the **Load template ID** field, enter a unique identifier (ID) for the load template.

3.  In the **Equipment** field, select the equipment to use for shipping the load.

4.  In the **Load height**, **Load width**, and **Load depth** fields, enter the dimensions of the load.

5.  In the **Max. allowed load volume** and **Max. allowed load weight** fields, enter the maximum allowed volume and weight of the load.

6.  In the **Maximum allowed gross weight** field, enter the maximum allowed gross weight of the load. The load’s gross weight includes both its tare weight and its loading weight.

7.  In the **Maximum number of freight pieces allowed** field, enter the maximum number of freight pieces that the load can contain.

8.  Select the **Stack load on floor** check box if you want to use floor loading. In a floor loading scenario, boxes are stacked floor-to-ceiling, wall-to-wall inside the container to maximize the inside capacity.

## Associate a load template with a new load

To associate a load template with a new load, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Load planning workbench**.

2.  Click **To new load**.

3.  In the **Load template ID** field, select a template.

## Related tasks

[Set up a transportation template](set-up-a-transportation-template.md)

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
<td><p><strong>Configuration key</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

