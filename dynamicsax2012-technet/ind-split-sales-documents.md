---
title: (IND) Split sales documents
TOCTitle: (IND) Split sales documents
ms:assetid: 6e97d0fb-a7bf-4dd8-9559-30c0c9955842
ms:mtpsurl: https://technet.microsoft.com/library/JJ677904(v=AX.60)
ms:contentKeyID: 49385880
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Split sales documents 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can split an invoice based on delivery addresses, sites, and service codes.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, in the left pane, click **Summary update**.

3.  In the **Split based on** field group, select the appropriate check boxes to post and split a confirmation, picking list, packing slip, or invoice when lines in a sales order have different delivery addresses, sites, and tax account numbers (TANs).

## Scenario 1

The **Invoice** check box in the **Delivery information** column is selected. A sales invoice that contains the following information is posted.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Line item</p></th>
<th><p>Delivery address</p></th>
<th><p>Tax account number</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Line item 1</p></td>
<td><p>Delivery address 1</p></td>
<td><p>TAN-ABCD67891A</p></td>
</tr>
<tr class="even">
<td><p>Line item 2</p></td>
<td><p>Delivery address 2</p></td>
<td><p>TAN-ABCE55527B</p></td>
</tr>
<tr class="odd">
<td><p>Line item 3</p></td>
<td><p>Delivery address 1</p></td>
<td><p>TAN-ABCD67891A</p></td>
</tr>
</tbody>
</table>


Invoice 1 is posted for line item 1 and line item 3, because these lines have the same delivery address and TAN.

Invoice 2 is posted for line item 2.

## Scenario 2

The **Packing slip** check box in the **Site** column is selected and unavailable.

If you create a sales order that has multiple line items, the same site dimension is selected for all line items. However, the TANs differ for at least one of the selected tax types.

When you post the packing slip, the site information is the same for the line items, but the packing slip must be split based on the TAN information. Therefore, the packing slip must be split based on sites and TANs.

## Scenario 3

The **Invoice** check box in the **Site** column is selected.

If you create a sales order that has multiple line items, the same site dimension is selected for all line items. However, the TANs differ for at least one of the selected tax types.

When you post the invoice, the site information is the same for the line items, but the invoice must be split based on the TAN information. Therefore, the invoice must be split based on sites and TANs.

## Scenario 4

The **Picking list** check box in the **Site** column is selected and unavailable.

If you create a sales order that has multiple line items, the same site dimension must be selected for all line items. However, the TANs can differ for at least one of the selected tax types.

When you post the picking list, the site information is the same for the line items, but the picking list must be split based on the tax registration number information. Therefore, the picking list must be split based on sites and TANs.

## See also

[(IND) Split purchase documents](ind-split-purchase-documents.md)

  


