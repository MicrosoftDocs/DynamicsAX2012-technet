---
title: About batch merges in inventory
TOCTitle: About batch merges in inventory
ms:assetid: 04d2b20c-22ff-4e06-a757-cef42ffb65a5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn505751(v=AX.60)
ms:contentKeyID: 59604025
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
- batch merges
- MsDynAx060.Forms.InventBatchJournalListPage
audience: Application User
ms.search.region: Global
---

# About batch merges in inventory 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



This topic provides information about consolidating two or more inventory batches into a merged batch. When you merge batches, calculations can help optimize the characteristics and batch attributes in the merged batch. After the source batches are selected, the merged batch can be reviewed and changed before it is posted. You can also transfer the batch merge to an inventory journal for approval, where inventory can be reserved or posted directly. When you post a merged batch, the inventory is adjusted for the source batches and the merged batch.

## Are there any prerequisites?

Yes, there are some things that you must set up before you can use the merge batch tools. The following table describes the prerequisites.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Journal names, inventory</strong></p></td>
<td><p>You must create a journal name to use by default when you post batch merges in inventory journals.</p>
<p>Optionally, although recommended, you can specify that reservations are automatically made when the batch merge is transferred to the inventory journal. Otherwise, there is a risk that a change is made to the on-hand inventory after the batch merge details are set up and the journal is posted. To enable auto-reservations for the journal name, in the <strong>Reservation</strong> field, select <strong>Automatic</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Inventory and warehouse management parameters</strong></p></td>
<td><p>You must specify the default journal name for the inventory journal. For more information, see <a href="about-journal-names.md">About journal names</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Released products</strong></p></td>
<td><p>The recommended settings for the item are as follows:</p>
<ul>
<li><p>If you want to automatically generate batch numbers for merged batches, you must assign the released product to a batch number group. You can also enter a batch number manually when you create a merged batch, or select an existing batch number. If you select an existing batch number, be sure that the selected batch has not been included in any inventory transactions.</p></li>
<li><p>If you are using shelf life or best before dates for the released product, the dates for a merged batch will be calculated based on the selection in the <strong>Batch merge date calculation</strong> field. The following options are available:</p>
<ul>
<li><p><strong>Earliest</strong> – The earliest date that is specified for a source batch that is selected for the batch merge.</p></li>
<li><p><strong>Latest</strong> - The latest date that is specified for a source batch that is selected for the batch merge.</p></li>
<li><p><strong>Manual</strong> – No calculation is made. If a date is the same on all source batches, a date will be suggested. If needed, you can change the date. If a date is not the same on the source batches, you can manually enter it.</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Batch number group</strong></p></td>
<td><p>Optional: To generate a batch number when you create a merged batch, you must assign a batch number group to the released product. Otherwise, you can enter a batch number manually. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa591648(v=ax.60)">Number groups (form)</a>.</p></td>
</tr>
</tbody>
</table>


## When would I want to merge batches of inventory?

The following scenarios are examples of when it would be useful to merge batches.

  - Sammy is walking through his warehouse, and notices that there are several batches of the same item that have low quantities. He is expecting to receive several new shipments, and he realizes that he can free some floor space by merging the odd quantities into a new batch.

  - Sammy is receiving inventory, and wants to combine the new batch with one that he has already to improve the batch attribute value of the existing batch.

## Can I merge batches across sites and legal entities?

No, you can only merge batches that have the same site and warehouse storage dimensions in one legal entity. However, you can specify a different location and pallet ID for the merged batch.

## What if the batches have different batch attribute values?

When you select the source batches to combine in the merged batch, Microsoft Dynamics AX will check whether the characteristics or attribute values are the same on all of the batches. When an attribute value is the same, a value will be suggested for the merged batch. If needed, you can change the value. Attribute values that are not the same are left blank for the merged batch, and you can enter these values manually.

If the batch attribute type for the attribute value is an integer or a fraction, and the values are not the same for all the source batches, the value will be calculated by using a weighted average calculation. The calculated value is rounded up or down to the nearest increment. If the value is blank for a source batch, the batch and its quantity are not included in the calculation.

**Example**

The following example illustrates a weighted average calculation for a merged batch. Two of the source batches have a blank value for a batch attribute type that is an integer.

The following attribute is assigned to the source batches.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Attribute</p></th>
<th><p>Minimum</p></th>
<th><p>Increment</p></th>
<th><p>Maximum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Grade</p></td>
<td><p>3</p></td>
<td><p>3</p></td>
<td><p>30</p></td>
</tr>
</tbody>
</table>


The source batches have the following attribute values for the Grade batch attribute.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Batch</p></th>
<th><p>Quantity</p></th>
<th><p>Attribute</p></th>
<th><p>Attribute value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>B1</p></td>
<td><p>10</p></td>
<td><p>Grade</p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p>B2</p></td>
<td><p>15</p></td>
<td><p>Grade</p></td>
<td><p>15</p></td>
</tr>
<tr class="odd">
<td><p>B3</p></td>
<td><p>20</p></td>
<td><p>Grade</p></td>
<td><p>20</p></td>
</tr>
<tr class="even">
<td><p>B4</p></td>
<td><p>25</p></td>
<td><p>Grade</p></td>
<td><p>Blank</p></td>
</tr>
<tr class="odd">
<td><p>B5</p></td>
<td><p>30</p></td>
<td><p>Grade</p></td>
<td><p>25</p></td>
</tr>
</tbody>
</table>


When you add these batches as source batches, the merged batch is assigned the following values.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Batch</p></th>
<th><p>Quantity</p></th>
<th><p>Attribute</p></th>
<th><p>Attribute value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>B6</p></td>
<td><p>100</p></td>
<td><p>Grade</p></td>
<td><p>21</p></td>
</tr>
</tbody>
</table>


The values and quantities for batches B1 and B4 are not included in the weighted average calculation. Therefore, the value for the merged batch is calculated as follows.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Value</p></th>
<th><p>Quantity (weight)</p></th>
<th><p>Relative weight</p></th>
<th><p>Relative weight * Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>15</p></td>
<td><p>15</p></td>
<td><p>0.230769231</p></td>
<td><p>3.461538462</p></td>
</tr>
<tr class="even">
<td><p>20</p></td>
<td><p>20</p></td>
<td><p>0.307692308</p></td>
<td><p>6.153846154</p></td>
</tr>
<tr class="odd">
<td><p>25</p></td>
<td><p>30</p></td>
<td><p>0.461538462</p></td>
<td><p>11.53846154</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>65, which is the total of the weights</p></td>
<td><p></p></td>
<td><p>Total: 21.5384615, rounded to 21, which is the nearest increment.</p></td>
</tr>
</tbody>
</table>


## What if the batches have different batch dates?

If the batches have different batch dates, some of the dates will be calculated based on the values in the **Batch dates** group. On the **Batch merge** form, on the **Merged batch** FastTab, the system will calculate values for the fields in the **Batch dates** group. These include the manufacturing, expiration, shelf advice, and best before dates. The dates are calculated based on settings for the item on the Released product details form in the **Item data** field group. If needed, you can change the values or enter them manually.

For all other dates, no calculation is made. The same principle is used for batch attribute values. If a date is the same for all of the source batches, this date will be suggested for the merged batch. If the date is not the same for all source batches, the date is blank on the merged batch and you can enter it manually.

## What if the dimensions are different on the batches that I want to merge?

Product dimensions, tracking dimensions, and storage dimensions are handled as follows:

  - **Product dimensions**– All product dimensions for the selected item must be the same. You cannot merge batches across product dimensions.

  - **Tracking dimensions** – A new batch number is automatically generated if a batch number group is specified for the item. If a batch number group is not assigned to an item, you can select an existing batch or enter the number manually. Serial numbers are transferred from the source batch to the inventory journal lines for the merged batch.

  - **Storage dimensions** – The site and warehouse storage dimensions must be the same for all of the source batches and the merged batch. However, you can specify a new location and pallet ID for the merged batch.

## How does posting work?

Posting works in two ways, depending on whether you are using an approval process for journals. You can use the **Transfer to journal** and **Post the batch merge** buttons to transfer the batch merge to a journal where it can be verified and posted, or you can post the batch merge directly. The key difference between the two actions is that transferring to a journal does not post the batch merge. Both actions will create a new batch if an existing batch is not selected, update all batch details and attribute values, and create an inventory journal.

  - **Transfer to journal** – Transfers the batch merge details to a new inventory journal. If you have set up automatic reservations, the quantities in the source batches are reserved. The details of the batch merge cannot be changed. If you must modify the batch merge, you must delete the journal.

  - **Post the batch merge** – Posts the batch merge directly.

You can approve the inventory journal for the batch merge from the **All batch merges** list page by clicking **Journal** \> **Post**.

After a journal is posted, you cannot change the details in the merged batch. After you transfer a batch merge to an inventory journal, you can change the details only if the journal is deleted.

## After I merged a catch weight item, why can’t I see the catch weight information on the inventory journal?

You can merge batches of catch weight items just like all other items. However, the catch weight information is not displayed on the inventory journal. We recommend that you verify the catch weight information before you transfer the batch merge to the inventory journal.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Merge inventory batches](merge-inventory-batches.md)

  


