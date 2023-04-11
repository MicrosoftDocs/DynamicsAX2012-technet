---
title: About credit notes
TOCTitle: About credit notes
ms:assetid: b16addba-6caa-485d-ac39-012d3837d06c
ms:mtpsurl: https://technet.microsoft.com/library/Hh242718(v=AX.60)
ms:contentKeyID: 36058976
author: tfehr
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About credit notes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When an amount on a customer invoice has a negative value, the invoice is classified as a credit note. When the document is printed, it has the title **Credit note**.

When you create a credit note to credit an amount that was previously invoiced, you must first select the invoiced amount for crediting. Then you create a credit note by following the same procedure that you use to create an ordinary customer invoice. That is, you must select the transactions that were previously posted on a customer invoice and then create and post a credit note proposal.

You can include transactions that are selected for crediting, credit transactions, and transactions that are posted on the same invoice or credit note. The document is then classified as either an invoice or a credit note, depending on whether the total amount is positive or negative.

## Crediting sales orders

The procedure for crediting sales orders is different than the procedure for crediting project transactions. The following table describes the differences.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction originating from</p></th>
<th><p>To be reversed to project</p></th>
<th><p>To be reversed to inventory</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Item consumption such as item journal, project purchase order, or item requirement.</p></td>
<td><p>Use the Select for credit note feature in Project management and accounting project.</p></td>
<td><p>Use the Crediting feature in Accounts receivable to create a credit note.</p></td>
</tr>
<tr class="even">
<td><p>Item delivery such as sales order.</p></td>
<td><p>Use the Sales order credit note feature in Sales and marketing to create a credit note.</p></td>
<td><p>Use the Crediting feature in Sales and marketing to create a credit note.</p></td>
</tr>
</tbody>
</table>


## See also

[Credit invoiced amounts in projects](credit-invoiced-amounts-in-projects.md)

[Select for credit note (form)](https://technet.microsoft.com/library/aa550205\(v=ax.60\))

  


