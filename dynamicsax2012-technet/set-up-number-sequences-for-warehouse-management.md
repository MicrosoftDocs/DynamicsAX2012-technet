---
title: Set up number sequences for warehouse management
TOCTitle: Set up number sequences for warehouse management
ms:assetid: 6a9b1711-3c41-44c6-8658-a6cf4da82235
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553166(v=AX.60)
ms:contentKeyID: 62200084
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Warehouse
- Number sequences
- Forms.WHSParameters
- MsDynAx060.Forms.WHSParameters
- warehouse parameters
- work transaction
---

# Set up number sequences for warehouse management 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Number sequences are used to generate unique identifiers for warehouse transactions. You must select noncontinuous number sequences in the **Warehouse management parameters** form for all warehouse management entities that require a unique identifier to be generated for a warehouse transaction. For more information about number sequences, see [Set up number sequences](set-up-number-sequences.md).

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.

2.  Click **Number sequences**, and then select the number sequence references. The following table describes some key number sequence references.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Work voucher</strong></p></td>
    <td><p>The unique ID for a voucher created for a work transaction.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Work creation number</strong></p></td>
    <td><p>The unique number that is generated for a transaction every time that work is created.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>License plate</strong></p></td>
    <td><p>The unique nine-digit ID for a license plate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Label ID</strong></p></td>
    <td><p>The unique ID for a label, such as a license plate label, printed by using a warehouse mobile device.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Work creation ID</strong></p></td>
    <td><p>The unique ID that is generated for a transaction every time that work is created.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Work grouping ID</strong></p></td>
    <td><p>The unique ID for a work group. A work group is a logical grouping of warehouse workers who use a mobile device to perform similar warehouse operations.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Release to warehouse ID</strong></p></td>
    <td><p>The unique ID for a transaction that is created for releasing loads or sales orders to a warehouse.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Container transaction ID</strong></p></td>
    <td><p>The unique ID for a transaction that is created for closing containers.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Temporary tote ID</strong></p></td>
    <td><p>The unique license plate ID that is assigned to a tote when it is put in a packing location.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Cluster ID</strong></p></td>
    <td><p>The unique ID for a work cluster.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Containerization process ID</strong></p></td>
    <td><p>The unique ID for a containerization wave step.</p></td>
    </tr>
    </tbody>
    </table>


## Related tasks

[Set up general warehouse parameters](set-up-general-warehouse-parameters.md)

[Create a work template](create-a-work-template.md)

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

