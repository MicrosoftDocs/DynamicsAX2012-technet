---
title: (BRA) Set up a withholding tax
TOCTitle: (BRA) Set up a withholding tax
ms:assetid: 01c5cd3b-d9e4-4ced-b148-fe5193957d27
ms:mtpsurl: https://technet.microsoft.com/library/Dn126100(v=AX.60)
ms:contentKeyID: 52075235
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up a withholding tax 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up a withholding tax code, a withholding tax type, and a calculation parameter to calculate withholding taxes for consultancy services or professional service payments. You can also enter values for the withholding tax code by using the **Withholding tax values** form.

**Example**

The following table explains how withholding tax is calculated as a percentage of a payment amount in a month.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice number</p></th>
<th><p>Invoice date</p></th>
<th><p>Invoice amount</p></th>
<th><p>Withholding tax code (Origin – Percentage of gross amount in a month)</p></th>
<th><p>Minimum limit</p></th>
<th><p>Payment date</p></th>
<th><p>Payment journal amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>123</p></td>
<td><p>November 15, 2013</p></td>
<td><p>BRL 4000.00</p></td>
<td><p>10 percent</p></td>
<td><p>BRL 5000.00</p></td>
<td><p>November 25, 2013</p></td>
<td><p>BRL 4000.00. Because the amount has not exceeded the minimum limit, no withholding tax is applicable to invoice 123.</p></td>
</tr>
<tr class="even">
<td><p>345</p></td>
<td><p>November 20, 2013</p></td>
<td><p>BRL 2000.00</p></td>
<td><p>10 percent</p></td>
<td><p>BRL 5000.00</p></td>
<td><p>November28, 2013</p></td>
<td><p>BRL 1400.00, which is the amount that remains after you deduct the withholding tax (BRL 2000 – BRL 600). BRL 600 is the net of withholding tax (6000*10%).</p>
<p>6000.00 is the sum of invoices 123 and 345, to which withholding taxes apply as a percentage of the payment amount in a month.</p></td>
</tr>
</tbody>
</table>


1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

2.  Click **New** to create a withholding tax code. In the **Withholding tax name** field, enter the name for the withholding tax code.

3.  In the **Brazilian tax withhold type** field, select a type of withholding tax from the following options:
    
      - **PIS** – The Programa de Integração Social (PIS) tax is withheld by vendors or customers for consultancy or professional service payments.
    
      - **COFINS** – The Contribuição para o Financiamente da Securidade Social (COFINS) tax is withheld by vendors or customers for consultancy or professional service payments.
    
      - **CSLL** – The Contribuição Social sobre Lucro Líquido (CSLL) tax is withheld by vendors or customers for consultancy or professional service payments.
    
      - **PCC** – The combination of PIS, COFINS, and CSLL tax codes. This option is used to withhold taxes by vendors or customers for consultancy or professional service payments.
    
      - **IR** – The Imposto de Renda Retido na Fonte (IR) tax is retained by vendors or customers at the time when the fiscal document is posted.

4.  On the **General** FastTab, in the **Currency** field, select the company currency for the calculation of the withholding tax payment.
    

    > [!NOTE]
    > <P>The withholding tax code currency should be the same as the default currency that is set up in the <STRONG>Legal entities</STRONG> form when <STRONG>Percentage of gross amount in month</STRONG> is selected in the <STRONG>Origin</STRONG> field.</P>



5.  On the **Calculation** FastTab, in the **Origin** field, select **Percentage of gross amount in month** to calculate withholding taxes.
    

    > [!NOTE]
    > <P>The withholding tax is calculated, taking into account all of the payments, including the sales tax, that are made to a vendor in the same calendar month. The withholding tax calculation includes all of the invoices that are due to be paid to a vendor during that month.</P>



6.  Click **Values** to enter the values for the withholding tax code. For more information, see [Withholding tax values (form)](https://technet.microsoft.com/library/aa615586\(v=ax.60\)).

7.  In the **Minimum limit** field, enter the minimum base amount for the calculation of the withholding tax.

8.  In the **Value** field, enter the percentage that is used for the calculation of the withholding tax.

## See also

[(BRA) Withholding tax codes (modified form)](https://technet.microsoft.com/library/dn126109\(v=ax.60\))

[(BRA) Legal entities (modified form)](https://technet.microsoft.com/library/jj710585\(v=ax.60\))

[(BRA) Vendors (modified form)](https://technet.microsoft.com/library/jj933505\(v=ax.60\))

[(BRA) Withholding tax payments inquiry (form)](https://technet.microsoft.com/library/dn126102\(v=ax.60\))

[(BRA) Set up a withholding tax group and attach it to a customer or vendor](bra-set-up-a-withholding-tax-group-and-attach-it-to-a-customer-or-vendor.md)

[(BRA) Set up an item withholding tax group](bra-set-up-an-item-withholding-tax-group.md)

  


