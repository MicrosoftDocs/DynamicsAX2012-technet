---
title: About options for entering fixed asset transactions
TOCTitle: About options for entering fixed asset transactions
ms:assetid: 3999e0cd-28b9-4577-bc2d-6d141ea43603
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570145(v=AX.60)
ms:contentKeyID: 39519103
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About options for entering fixed asset transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up Fixed assets for integration with Accounts payable, Accounts receivable, Procurement and sourcing, and General ledger. You can also transfer items in Inventory management to Fixed assets if you want to use those items internally.

## Accounts payable

You can enter Fixed assets transactions in the **Journal voucher** form. This form can be opened from the **Invoice journal** form. (Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**. Click **Lines**.)

You can also open the **Journal voucher** form from the **Invoice approval journal** form. (Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**. Click **Lines**).

In the **Offset account type** field, select **Fixed assets**. Then, in the **Offset account** field, select a fixed asset number. On the **Fixed assets** tab, enter values in the **Transaction type** and **Value model** fields.

## Accounts receivable

You can enter Fixed assets transactions in the **Free text invoice** form. (Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**. Select a free text invoice, and then, on the **Action Pane**, click **Edit**.) In the **Free text invoice** form, in the **Invoice lines** grid, select a line item. Click the **Line details** FastTab. Enter the fixed asset number and value model for the disposal transaction. For free text invoices, the fixed asset transaction type is always **Disposal - sale**.

## Procurement and sourcing

You can enter Fixed assets transactions in the **Purchase order** form. (Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click **Purchase order**.) Enter the required information to create a purchase order, and then click **OK**. In the **Purchase order** form, click the **Line details** FastTab. Then, on the **Fixed assets** tab, enter information about the fixed asset group.

To post an acquisition transaction for an existing fixed asset, specify the fixed asset number, value model, and transaction type. The fixed asset cannot be posted if any of this information is missing. To post an acquisition transaction for a new fixed asset, select the **New fixed asset?** check box, and then select the fixed asset group to assign the new asset to. However, no fixed asset fields are available for a line if the item is in an inventory model group that uses a standard cost inventory model. Additionally, the options that are defined in the **Fixed assets parameters** form determine whether you can post acquisition transactions from the purchasing modules.

When a purchase order or the **Inventory to fixed assets** journal is used to acquire fixed assets, the inventory value is affected.

## General ledger

Any fixed asset transaction type can be posted in the **General journal** form. (Click **General ledger** \> **Journals** \> **General journal**.)

You can also use journals in Fixed assets to post fixed asset transactions.

## Options for entering fixed asset transaction types

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type</p></th>
<th><p>Module</p></th>
<th><p>Options</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Acquisition</strong>, <strong>Acquisition adjustment</strong></p></td>
<td><p><strong>Fixed assets</strong></p></td>
<td><p><strong>Fixed assets</strong></p>
<p><strong>Inventory to fixed assets</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>General ledger</strong></p></td>
<td><p><strong>General journal</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Accounts payable</strong></p></td>
<td><p><strong>Invoice journal</strong></p>
<p><strong>Invoice approval journal</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Procurement and sourcing</strong></p></td>
<td><p><strong>Purchase order</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Depreciation</strong></p></td>
<td><p><strong>Fixed assets</strong></p></td>
<td><p><strong>Fixed assets</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>General ledger</strong></p></td>
<td><p><strong>General journal</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Disposal</strong></p></td>
<td><p><strong>Fixed assets</strong></p></td>
<td><p><strong>Fixed assets</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>General ledger</strong></p></td>
<td><p><strong>General journal</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Accounts receivable</strong></p></td>
<td><p><strong>Free text invoice</strong></p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If a transaction is entered incorrectly, you can reverse it. For more information, see <A href="reverse-a-transaction.md">Reverse a transaction</A>.</P>



## See also

[Process assets created from Accounts payable](process-assets-created-from-accounts-payable.md)

[About fixed assets integration](about-fixed-assets-integration.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

