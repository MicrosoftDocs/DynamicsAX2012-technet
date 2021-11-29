---
title: (BRA) About calculation of taxes
TOCTitle: (BRA) About calculation of taxes
ms:assetid: 8f5b0f9e-b0da-48d3-8a21-ae0ac49ef9b1
ms:mtpsurl: https://technet.microsoft.com/library/JJ822918(v=AX.60)
ms:contentKeyID: 50117575
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ICMS
- Brazilian taxes
- fiscal value
- IPI
- BR - 00017
- BR - 00032
audience: Application User
ms.search.region: Brazil
---

# (BRA) About calculation of taxes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX calculates Brazilian taxes based on the tax type that you specify for the sales tax code. You can set up and calculate sales taxes on sales, purchases, transfers between fiscal establishments, delivery of items to a third party, or receipt of items from a third party.

You can set up taxation codes for Imposto sobre Circulação de Mercadorias e Serviços (ICMS), Imposto sobre Produtos Industrializados (IPI), Program de Integracao Social (PIS), and Contribuição para Financiamento da Seguridade Social (COFINS) taxes. The taxation codes are used for fiscal reporting and generating federal electronic fiscal documents (NF-e). You can also set up taxation codes for other tax types. When you set up a taxation code for a tax type, you assign a fiscal value to indicate the type of treatment that applies to taxes, such as taxable, not taxable or exempt, or taxable without credit. When a taxation code is not set up for a tax type, you can set up the fiscal value by selecting the **Without tax credit** and **Exempt** check boxes in the **Sales tax groups** and **Item sales tax groups** forms. Sales taxes are calculated and saved in the **Posted sales tax** form.

You can specify a default taxation code for the sales tax code in the **Taxation code** field on the **Calculation** FastTab in the **Sales tax codes** form. You can also specify the taxation code for a sales tax code:

  - When you attach the sales tax code to a sales tax group and the sales tax code is exempt.

  - When you attach the sales tax code to an item sales tax group.

When you create and post tax transactions from sales orders, purchase orders, free text invoices, or project invoice proposals, the taxes are calculated based on either the fiscal value of taxation codes that are selected in the **Fiscal value** field in the **Taxation code** form, or the fiscal value that is determined based on the **Without tax credit** and **Exempt** check boxes in the **Sales tax groups** and **Item sales tax groups** forms. The tax base and tax amount are displayed in the **Posted sales tax** and **Temporary sales tax transactions** forms, as follows:

  - For transactions with taxation codes that have a **1. with credit/debit** fiscal value, or item sales tax groups for which the **Without tax credit** check box is not selected, the amount that the sales tax is calculated for is equal to the taxable base amount. Sales tax is calculated according to the tax rate and is updated in the **Actual sales tax amount** field.

  - For transactions with taxation codes that have a **2. without credit/debit (exempt or not taxable)** fiscal value, or sales tax groups or item sales tax groups for which the **Exempt** check box is selected, the exempt base amount is equal to the transaction value, and no tax amount is calculated.

  - For transactions with taxation codes that have a **3. without credit/debit (other)** fiscal value, or item sales tax groups for which the **Without tax credit** check box is selected, the other base amount is equal to the transaction value. The sales tax amount is calculated according to the tax rate and is updated in the **Other tax amount** field.

## Examples

For a base transaction amount of BRL 1,000.00 and a tax rate of 18 percent, Microsoft Dynamics AX calculates the taxes as follows for the different fiscal values.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Fiscal value</strong></p></th>
<th><p><strong>Amount origin</strong></p></th>
<th><p><strong>Actual sales tax amount</strong></p></th>
<th><p><strong>Exempt base amount</strong></p></th>
<th><p><strong>Other base amount</strong></p></th>
<th><p><strong>Other tax amount</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>1. with credit/debit</strong></p></td>
<td><p>BRL 1,000.00</p></td>
<td><p>BRL 180.00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>2. without credit/debit (exempt or not taxable)</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>BRL 1,000.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>3. without credit/debit (other)</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>BRL 1,000.00</p></td>
<td><p>BRL 180.00</p></td>
</tr>
</tbody>
</table>


For a base transaction amount of BRL 1,000.00, tax rate of 18 percent, and tax reduction percentage of 40 percent, Microsoft Dynamics AX calculates the taxes as follows for the different fiscal values.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Fiscal value</strong></p></th>
<th><p><strong>Amount origin</strong></p></th>
<th><p><strong>Actual sales tax amount</strong></p></th>
<th><p><strong>Exempt base amount</strong></p></th>
<th><p><strong>Other base amount</strong></p></th>
<th><p><strong>Other tax amount</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>1. with credit/debit</strong></p></td>
<td><p>BRL 600.00</p></td>
<td><p>BRL 108.00</p></td>
<td><p>BRL 400.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>2. without credit/debit (exempt or not taxable)</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>BRL 1,000.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>3. without credit/debit (other)</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>BRL 400.00</p></td>
<td><p>BRL 600.00</p></td>
<td><p>BRL 108.00</p></td>
</tr>
</tbody>
</table>


For sales transactions with taxation codes that have a **1. with credit/debit** fiscal value, or item sales tax groups for which the **Without tax credit** check box is not selected: the actual sales tax amount is posted to the main accounts for which **Sales tax** and **Sales tax expense** are selected in the **Posting type** field in the **Accounts for automatic transactions** form. For more information, see [Accounts for automatic transactions (form)](https://technet.microsoft.com/library/aa548973\(v=ax.60\)).

For purchase transactions with taxation codes that have a **1. with credit/debit** fiscal value, or item sales tax groups for which the **Without tax credit** check box is not selected: the actual sales tax amount is posted to the main accounts for which **Sales tax** is selected in the **Posting type** field in the **Accounts for automatic transactions** form.

## See also

[(BRA) Taxation code (form)](https://technet.microsoft.com/library/jj682104\(v=ax.60\))

[(BRA) Posted sales tax (modified form)](https://technet.microsoft.com/library/jj710417\(v=ax.60\))

[(BRA) Set up tax codes](bra-set-up-tax-codes.md)

[(BRA) Set up and calculate tax on sales and purchases](bra-set-up-and-calculate-tax-on-sales-and-purchases.md)

  


