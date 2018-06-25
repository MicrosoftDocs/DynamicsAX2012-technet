---
title: Create disposition codes
TOCTitle: Create disposition codes
ms:assetid: 31e3a9da-bd53-40da-bbdf-4f75c9bd08ab
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553158(v=AX.60)
ms:contentKeyID: 62200052
ms.date: 04/23/2014
mtps_version: v=AX.60
f1_keywords:
- disposition
- Forms.WHSDispositionTable
- work template
- MsDynAx060.Forms.WHSDispositionTable
- inventory status
- return disposition code
---

# Create disposition codes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to create disposition codes for the inbound receiving process. Disposition codes are a collection of rules that are used when damaged items are received. For example, when a work user uses a mobile device to receive items that were damaged, the user must scan a disposition code for damaged items. Microsoft Dynamics AX uses the disposition codes to generate an inventory status and a work template, and then searches for the location directive with the same disposition code to determine where to put away the returned items.

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Disposition codes**.

2.  Click **New** to create a disposition code.

3.  In the **Inventory status** field, select the inventory status of the received items.

4.  In the **Work template code** field, select a work template code that is associated with a work order type, return order, or purchase order. You assign a work template to a disposition code only when you want to override the work template.

5.  In the **Return disposition code** field, select a return disposition code for a sales return order.
    

    > [!NOTE]
    > <P>After you select a <STRONG>Return disposition code</STRONG>, the disposition code is applicable only for the sales order return process.</P>



## Related tasks

[Set up mobile device menus to display work or activities](set-up-mobile-device-menus-to-display-work-or-activities.md)

[Create a work template](create-a-work-template.md)

[Set up an inventory status](set-up-an-inventory-status.md)

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

