---
title: Merge inventory batches
TOCTitle: Merge inventory batches
ms:assetid: aafee3e6-dcba-480e-83c4-f79aef7830dd
ms:mtpsurl: https://technet.microsoft.com/library/Dn505745(v=AX.60)
ms:contentKeyID: 59604020
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- merge
- combine
- batch
- batches
- batch merge
- Forms.InventBatchJournalListPage
- merges
- MsDynAx060.Forms.InventBatchJournalListPage
audience: Application User
ms.search.region: Global
---

# Merge inventory batches 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to merge two or more inventory batches.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<td><p>Journal name</p></td>
<td><p>Create or select a journal name to use by default when you post a batch merge.</p></td>
</tr>
<tr class="even">
<td><p>Inventory and warehouse management parameters</p></td>
<td><p>In the <strong>Inventory and warehouse management parameters</strong> form, on the <strong>Journals</strong> page, select the journal name to use for posting batch merges.</p>
<p>To reserve inventory when you transfer the batch merge to an inventory journal, you must select <strong>Automatic</strong> in the <strong>Reservation</strong> field for the journal name. If you select <strong>Explosion</strong> or <strong>Manual</strong>, reservations are not made. If you do not reserve the inventory, the information in the source batches can change while the journal is waiting for approval.</p></td>
</tr>
<tr class="odd">
<td><p>Shelf life dates</p></td>
<td><p>If you are using shelf life, you must specify how to calculate the dates for the items. You define this in the <strong>Released products</strong> form in the <strong>Item data</strong> field group. In the <strong>Batch merge date calculation</strong> field, you must also specify whether the date is the earliest or latest possible, or enter the date manually. The default setting is <strong>Manual</strong>. To include an item in a batch merge, it must be assigned to a batch tracking dimension.</p></td>
</tr>
</tbody>
</table>


## 1\. Select the batches that you want to merge

You can combine two or more batches in a batch merge.

To select the batches that you want to merge, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Batches** \> **All batch merges**.

2.  On the **Action Pane**, click **Batch merge**.

3.  In the **Item number** field, select the item that you want to select batches for.

4.  In the **Product dimensions** and **Storage dimensions** field groups, enter all required dimensions.

5.  On the **Source batches** FastTab, in the **Batch number** field, select a batch and then click **Add**.
    

    > [!TIP]
    > <P>The source batches must have on-hand inventory. When you select a source batch, click the <STRONG>On-hand</STRONG> tab to determine whether the batch has on-hand inventory.</P>
    > <P>After you have selected a source batch, the <STRONG>Item number</STRONG> field is not available. To select a different item, you must delete all of the source batch selections.</P>



## 2\. Enter the details for the merged batch

When you select source batches, some of the details are transferred to the merged batch if they are the same on all of the selected source batches. If needed, you can change the details in the merged batch.

To enter the details for the merged batch, follow these steps:

1.  On the **Merged batch** FastTab, in the **Batch number** field, do one of the following:
    
      - Select the identifier for the batch that will be the merged batch. This requires that the batch is already created, and that the batch has not been included in transactions.
    
      - Type an identifier for the merged batch.
    
      - Leave the field blank. If batch numbering is enabled for the batch number group that is associated with the item, you can leave this field blank. The system will generate a batch number for the merged batch.

2.  Enter the characteristics and attributes for the merged batch.
    

    > [!NOTE]
    > <P>The system will suggest values for the merged batch, as follows:</P>
    > <UL>
    > <LI>
    > <P><STRONG>Batch disposition</STRONG> and <STRONG>Vendor batch</STRONG> field groups - Values are suggested in these fields if all of the selected source batches have the same value. If the values are different on the source batches, no suggestions are made and you can enter them manually.</P>
    > <LI>
    > <P><STRONG>Batch dates</STRONG> field group - Suggested values are calculated based on the selection in the <STRONG>Batch merge date calculation</STRONG> field on the released product, and the dates in the source batches. The calculation method can be <STRONG>Earliest</STRONG>, <STRONG>Latest</STRONG>, or <STRONG>Manual</STRONG>. The earliest and latest calculation methods will suggest the earliest or latest dates that are specified on the source batch.</P></LI></UL>



3.  On the **Merged batch** FastTab, click the **Batch attributes** tab, and then review the attributes for the source batches and merged batch. To make comparisons easier, the **Batch details** and **Batch attributes** tabs for the **Source batches** and **Merged batch** FastTabs are synchronized.

4.  Optional: To make sure that the information is current, click **Refresh**.

5.  Optional: To display dimensions for each source batch, click **Dimensions display**.

## 3\. Post the batch merge or transfer it for approval

If you are using an approval process for inventory journals, you can either post the batch merge directly or transfer it to an inventory journal where it can be posted later.


> [!NOTE]
> <P>After you post a batch merge directly, the merge is complete and you cannot change the details in the merged batch. After you transfer a batch merge to an inventory journal, you can change the details only if you reject the batch merge by deleting the inventory journal.</P>



To post the batch merge or transfer it to an inventory journal, follow these steps:

  - On the **Action Pane**, click one of the following:
    
      - Click **Post the batch merge** to post the batch merge directly.
    
      - Click **Transfer to journal** to transfer the batch merge to an inventory journal, where it can be posted.

## 4\. Approve or reject a batch merge that is transferred to an inventory journal

After a batch merge is transferred to an inventory journal, you cannot change the details of the merged batch. The merge is not completed until it is posted.

To approve or reject a batch merge, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Batches** \> **All batch merges**.

2.  Select the batch merge that you want to view the journal for.
    

    > [!TIP]
    > <P>The <STRONG>Posted</STRONG> check box indicates whether the journals are posted. To filter the list, type <STRONG>No</STRONG> in the <STRONG>Type to filter</STRONG> field, and then select <STRONG>Posted</STRONG> in the filter list.</P>



3.  On the **Action Pane**, click **Journal**.

4.  Optional: To view the details in the journal, click **Lines**.

5.  To approve or reject the batch merge, use one of the following methods:
    
      - Click **Post** to complete the batch merge.
    
      - Click **Delete** to reject the batch merge.

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
<td><p><strong>Trade</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p><strong>Warehouse manager</strong></p>
<p><strong>Materials manager</strong></p>
<p><strong>Quality control manager</strong></p>
<p><strong>Production manager</strong></p>
<p><strong>Warehouse worker</strong></p>
<p><strong>Quality control clerk</strong></p>
<p><strong>Receiving clerk</strong></p>
<p><strong>Shipping clerk</strong></p>
<p><strong>Machine operator</strong></p></td>
</tr>
</tbody>
</table>


## See also

[About batch merges in inventory](about-batch-merges-in-inventory.md)

  


