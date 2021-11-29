---
title: (RUS) VAT operation types for export transactions
TOCTitle: (RUS) VAT operation types for export transactions
ms:assetid: 81b10659-c750-420a-b795-8b77bd891234
ms:mtpsurl: https://technet.microsoft.com/library/JJ678422(v=AX.60)
ms:contentKeyID: 49387651
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- VAT
- operation type
audience: Application User
ms.search.region: Russia
---

# (RUS) VAT operation types for export transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Export sales are taxable at a value-added tax (VAT) rate of zero percent. However, the taxpayer can apply this tax rate only after receiving a confirmation from the tax authorities within a specified period. The taxpayer must collect the necessary documents that confirm the VAT rate of zero percent for export sales within this period. If the tax authority provides this confirmation within the specified period, the tax is calculated at a VAT rate of zero percent and is included in the sales book. If the confirmation is not received in time, the taxpayer must pay tax at the standard VAT rate of 10 percent or 18 percent, along with any tax that is overdue from the export confirmation. Factures are calculated for a VAT rate of zero percent, a VAT rate of 10 percent, and a VAT rate of 18 percent, and are recorded in the sales book.

To apply export VAT, complete the following tasks:

  - Set the tax type to a VAT rate of zero percent.

  - Set the tax code that is used for domestic trading operations as the standard VAT rate.

  - Set the VAT operation type in the **Sales tax codes** form.

VAT operation types are rules that are used for preliminary processing of export factures. The value of an operation type is automatically assigned to the facture based on the export date, confirmation date, and expiration date.

The following table describes the operation types.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Operation type</p></th>
<th><p>Condition</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>VAT 0%</strong></p></td>
<td><p>A VAT rate of zero percent is applied when the export VAT is confirmed within the expiration period.</p></td>
<td><p>The confirmation date for this operation type is in the current period and is less than the expiration date. The facture is added to the sales book with a VAT rate of zero percent.</p></td>
</tr>
<tr class="even">
<td><p><strong>Unconfirmed VAT 0%</strong></p></td>
<td><p>An unconfirmed VAT rate of zero percent is applied when the export VAT is not confirmed within the expiration period.</p></td>
<td><p>The confirmation date for this operation type is not entered, and the expiration date is in the current period. Factures with this operation type are added to the sales book with the standard VAT rate.</p></td>
</tr>
<tr class="odd">
<td><p><strong>VAT 0% with correction</strong></p></td>
<td><p>A VAT rate of zero percent with correction is applied when the export VAT is confirmed on time, but export factures were added to the sales book with the standard VAT rate.</p></td>
<td><p>The facture is included in the sales book with a VAT rate of zero percent, and the reporting period in which the facture was included with the standard rate is corrected.</p></td>
</tr>
<tr class="even">
<td><p><strong>Unconfirmed VAT 0% with correction</strong></p></td>
<td><p>An unconfirmed VAT rate of zero percent with correction is applied when the export VAT is not confirmed on time, but export factures were added to the sales book with a VAT rate of zero percent.</p></td>
<td><p>VAT is calculated by using the standard local rate. The factures for the calculated amounts are created and included in the sales book, and the period in which the facture was included with a VAT rate of zero percent is corrected.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Overdue confirmation</strong></p></td>
<td><p>An overdue confirmation is applied when the export VAT is confirmed after the expiration date, and the facture is added to the sales book by using the standard VAT rate.</p></td>
<td><p>The facture is included in the sales book with a VAT rate of zero percent, the reporting period in which the facture was included with the standard rate is corrected, and the facture to cancel the unconfirmed VAT rate of zero percent is created and included in the purchase book.</p></td>
</tr>
</tbody>
</table>


## See also

[(RUS) Define parameters for export operations](rus-define-parameters-for-export-operations.md)

[(RUS) Create an export facture](rus-create-an-export-facture.md)

  


