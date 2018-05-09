---
title: (RUS) Amount difference factures for sales and purchase orders
TOCTitle: (RUS) Amount difference factures for sales and purchase orders
ms:assetid: 65247235-0e3a-4b04-a306-c800069911d2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853188(v=AX.60)
ms:contentKeyID: 50396469
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Amount difference factures for sales and purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can generate an amount difference facture, you must create and post a facture for a purchase order or sales order. After posting the facture, settle the facture transactions to generate the amount differences based on the exchange rates.

Amount difference factures are corrections for factures. Based on the amount differences, the original factures are displayed in the sales book and purchase book. In the sales book, they are displayed as separate lines, but have the same facture identifier and display the same date as the original facture. In the purchase book, they are displayed as a total line, with the amount difference sum added to the original facture amount.

You can recalculate the cost of the original facture, taking into account the amount difference. In the additional list, the original facture amount is marked with a negative sign, and the recalculated facture amount is marked with a positive sign. You can print the amount differences from the **Facture journal** form in the following ways:

  - Include all amount difference factures.

  - Include only marked amount difference factures.

**Example**

The following is an example of how amount differences are calculated for a contract.

The cost of the received goods is 100 standard units, and the tax accounting period is monthly. Payments are made in RUB (rubles) by using the currency rate on the payment date.

If the currency rate is 32 RUB for one standard unit, two invoice lines are created, as shown in the following table.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Standard units</p></th>
<th><p>Invoice amount</p></th>
<th><p>VAT percent</p></th>
<th><p>Standard units (including VAT percentage)</p></th>
<th><p>Invoice amount (including VAT percentage)</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>40</p></td>
<td><p>1280</p></td>
<td><p>18</p></td>
<td><p>6.10</p></td>
<td><p>195.20</p></td>
</tr>
<tr class="even">
<td><p>60</p></td>
<td><p>1920</p></td>
<td><p>10</p></td>
<td><p>5.45</p></td>
<td><p>174.20</p></td>
</tr>
</tbody>
</table>


If the currency rate changes from 32 RUB to 28 RUB, the payment for the received goods also changes. For 20 standard units, the payment becomes 560 RUB. Therefore, during transaction settlement, an amount difference (28 – 32) is generated and displayed on the facture lines. You can also calculate the total cost and total tax for every tax code.

Here, **A** is the corrected number of standard units based on the amount difference for the first facture line. The proportion for VAT tax calculation is:

20:100 = A: 40

Therefore, A = 20 \* 40 / 100 = 8

Therefore, the correction for the first line is:

8 \* (28 – 32) = –32 RUB

Here, **B** is the corrected number of standard units based on the amount difference for the second facture line. The proportion for the VAT calculation is:

20:100 = B: 60

Therefore, B = 20 \* 60 / 100 = 12

Therefore, the correction for the second line is:

12 \* (28 – 32) = –48 RUB

VAT is applied to the amount difference. For VAT at 18 percent, the value is:

(32 / 118) \* 18 = 4.88 RUB

Similarly, for VAT at 10 percent, the value is:

(48 / 110) \* 10 = 4.36 RUB

## See also

[(RUS) Set up accounts payable parameters for amount differences](rus-set-up-accounts-payable-parameters-for-amount-differences.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

