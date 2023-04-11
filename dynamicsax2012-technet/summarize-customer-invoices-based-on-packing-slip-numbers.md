---
title: Summarize customer invoices based on packing slip numbers
TOCTitle: Summarize customer invoices based on packing slip numbers
ms:assetid: 13265c84-76c3-4b01-8e32-e85318776400
ms:mtpsurl: https://technet.microsoft.com/library/Gg230936(v=AX.60)
ms:contentKeyID: 37822138
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Summarize customer invoices based on packing slip numbers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create customer invoices that correspond to packing slip numbers. Each invoice can include line items from multiple sales orders, provided that the line items are included on the same packing slip. You can then invoice customers for each delivery, regardless of when the items were ordered.

## Example

You use the **Summary update for** field in the sales order **Posting invoice** form to summarize the customer invoices. You have three sales orders and three packing slips, as shown in the following table. All packing slips have the same invoice account and currency code.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Packing slip 1: June 15</p></th>
<th><p>Packing slip 2: June 17</p></th>
<th><p>Packing slip 3: June 19</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales order 1, line 1</p></td>
<td><p>Sales order 2, line 2</p></td>
<td><p>Sales order 3, line 2</p></td>
</tr>
<tr class="even">
<td><p>Sales order 1, line 2</p></td>
<td><p>Sales order 2, line 3</p></td>
<td><p>Sales order 3, line 3</p></td>
</tr>
<tr class="odd">
<td><p>Sales order 2, line 1</p></td>
<td><p>Sales order 3, line 1</p></td>
<td><p>Sales order 1, line 3</p></td>
</tr>
</tbody>
</table>


If you select **Packing slip** in the **Summary update for** field, the invoices are summarized as shown in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice 1: June 30</p></th>
<th><p>Invoice 2: June 30</p></th>
<th><p>Invoice 3: June 30</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales order 1, line 1</p></td>
<td><p>Sales order 2, line 2</p></td>
<td><p>Sales order 3, line 2</p></td>
</tr>
<tr class="even">
<td><p>Sales order 1, line 2</p></td>
<td><p>Sales order 2, line 3</p></td>
<td><p>Sales order 3, line 3</p></td>
</tr>
<tr class="odd">
<td><p>Sales order 2, line 1</p></td>
<td><p>Sales order 3, line 1</p></td>
<td><p>Sales order 1, line 3</p></td>
</tr>
</tbody>
</table>


If you select **None** in the **Summary update for** field to indicate that you do not want to summarize the invoices, the invoices are based on the sales order documents, as shown in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice 1: June 30</p></th>
<th><p>Invoice 2: June 30</p></th>
<th><p>Invoice 3: June 30</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales order 1, line 1</p></td>
<td><p>Sales order 2, line 1</p></td>
<td><p>Sales order 3, line 1</p></td>
</tr>
<tr class="even">
<td><p>Sales order 1, line 2</p></td>
<td><p>Sales order 2, line 2</p></td>
<td><p>Sales order 3, line 2</p></td>
</tr>
<tr class="odd">
<td><p>Sales order 1, line 3</p></td>
<td><p>Sales order 2, line 3</p></td>
<td><p>Sales order 3, line 3</p></td>
</tr>
</tbody>
</table>


## Summarize customer invoices

1.  Click **Accounts receivable** \> **Periodic** \> **Sales update** \> **Invoice**.

2.  In the **Quantity** field, select **Packing slip**.

3.  Click **Select**, and then modify the query, if changes are required. For example, you can select a range of dates for the **Ship date** field.

4.  Click **OK** to close the **Sales update** form.

5.  Select the **Posting** check box.

6.  In the **Print options** field group, make any selections that are required.

7.  On the **Other** tab, in the **Summary update for** field, select **Packing slip**.

8.  Click **Select packing slip**.

9.  In the **Select packing slip** form, review the list of packing slips in the upper pane. By default, all packing slips that are posted for the sales orders are included on the invoices. If you do not want the invoices to include some packing slips, clear the **Include** check box for those packing slips.

10. Click **OK** to close the **Select packing slip** form.

11. Click **Arrange**. The sales orders and lines are grouped by packing slip number.

12. Click the **Lines** tab. This tab displays the packing slip number and ship date. The packing slip number and ship date are also printed on the invoice, if you print invoice documents.

13. Click **OK**. The customer invoices are posted and printed.

## See also

[Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\))

[Select sales order packing slip (form)](https://technet.microsoft.com/library/hh580614\(v=ax.60\))

[Key tasks: Customer invoices](key-tasks-customer-invoices.md)

  


