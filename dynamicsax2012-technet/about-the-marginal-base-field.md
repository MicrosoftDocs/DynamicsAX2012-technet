---
title: About the Marginal base field
TOCTitle: About the Marginal base field
ms:assetid: 57ba4f23-6fea-41dc-a0b9-9affd1873fb2
ms:mtpsurl: https://technet.microsoft.com/library/Aa549061(v=AX.60)
ms:contentKeyID: 36057334
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About the Marginal base field 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

On the **Calculation** FastTab of the **Sales tax codes** form, you define how the sales tax calculation of the selected sales tax code is applied to the tax base amounts on the invoice. You do this by selecting an amount category in the **Marginal base** field and an appropriate value in the **Calculation method** field.

Various combinations of values in these fields produce very different sales tax calculations, as shown by the following examples. The examples use the same tax interval values, which are set up for each tax code in the **Values** form. To open this form, click **Values** in the **Sales tax codes** form.


> [!IMPORTANT]
> <P>If the marginal base on one or more of your sales tax codes is based on line or unit, the value of the <STRONG>Calculation method</STRONG> field in the <STRONG>General ledger parameters</STRONG> form must be set to <STRONG>Line</STRONG>.</P>
> <P>In the United States, sales tax is usually calculated for each invoice line, and the total sales tax on the invoice is the sum of sales taxes on each line. In Europe, it is common to total the base amount for all invoice lines. The calculated base is then used to calculate taxes.</P>



## Net amount per line

Select this option to calculate sales tax based on the net amount for the invoice lines, excluding any other taxes.

## Example

The sales tax rates are set up in the following intervals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Amount interval</p></th>
<th><p>Tax rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0 - 50</p></td>
<td><p>30%</p></td>
</tr>
<tr class="even">
<td><p>50 - 100</p></td>
<td><p>20%</p></td>
</tr>
<tr class="odd">
<td><p>100 - 0 (&gt; 100)</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>The upper limit of zero (0) in the last interval means that all amounts that exceed 100 are included in the interval.</P>



**Marginal base**: **Net amount per line**

**Calculation method**: **Interval**

You buy eight lamps that cost 25.00 each. The net amount for the invoice line is 200.00.

The tax is calculated as follows:

Total sales tax = 50 x 30% + 50 x 20% + 100 x 10% = 15 + 10 + 10 = 35.00

Total invoice amount = 200.00 + 35.00 = 235.00

**Variation**

If the invoice is created by using two lines with four items on each line, the net amount per line is 100.00 and the sales tax is calculated as follows:

Sales tax line 1 = 50 x 30% + 50 x 20% = 15 + 10 = 25.00

Sales tax line 2 = 50 x 30% + 50 x 20% = 15 + 10 = 25.00

Total sales tax = 25.00 + 25.00 = 50.00

Total invoice amount = 200.00 + 50.00 = 250.00

## Net amount per unit

Select this option to calculate sales tax based on the value of each unit, excluding any other taxes. This can also involve the price of the unit that is specified in the **Unit** field, if the sales tax code uses this field.

## Example

The sales tax rates are set up in the following intervals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Amount</p></th>
<th><p>Tax rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0 - 50</p></td>
<td><p>30%</p></td>
</tr>
<tr class="even">
<td><p>50 - 100</p></td>
<td><p>20%</p></td>
</tr>
<tr class="odd">
<td><p>100 - 0 (&gt; 100)</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>


**Marginal base**: **Net amount per unit**

**Calculation method**: **Whole amount**

You buy eight lamps that cost 25.00 each. The net amount for the invoice line is 200.00.

The tax is calculated as follows:

Sales tax per unit = 25.00 x 30% = 7.50

Total sales tax = 7.50 x 8 units = 60.00

Total invoice amount = 200.00 + 60.00 = 260.00

## Net amount of invoice balance

Select this option to calculate sales tax based on the total value for the invoice, excluding any other taxes.

## Example

The sales tax rates are set up in the following intervals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Amount</p></th>
<th><p>Tax rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0 - 50</p></td>
<td><p>30%</p></td>
</tr>
<tr class="even">
<td><p>50 - 100</p></td>
<td><p>20%</p></td>
</tr>
<tr class="odd">
<td><p>100 -0 (&gt; 100)</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>


**Marginal base**: **Net amount of invoice balance**

**Calculation method**: **Interval**

You buy eight lamps that cost 25.00 each. The net amount for the invoice line is 200.00.

The tax is calculated as follows:

Total sales tax = 50 x 0.30 + 50 x 0.20 + 100 x 0.10 = 15 + 10 + 10 = 35.00

Total invoice amount = 200.00 + 35.00 = 235.00


> [!WARNING]
> <P>It makes no difference how many lines the invoice has, because the value of the <STRONG>Marginal base</STRONG> field is <STRONG>Net amount of invoice balance</STRONG>.</P>



## Gross amount per line

Select this option to calculate sales tax based on the value of the line. This includes any other taxes.


> [!NOTE]
> <P>In a sales tax group, you can only have one sales tax code with this selection in the <STRONG>Marginal base</STRONG> field.</P>



## Example

The sales tax rates are set up in the following intervals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Amount</p></th>
<th><p>Tax rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0 - 50</p></td>
<td><p>30%</p></td>
</tr>
<tr class="even">
<td><p>50 - 100</p></td>
<td><p>20%</p></td>
</tr>
<tr class="odd">
<td><p>100 - 0 (&gt; 100)</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>


There is a special duty of 5.00 on each lamp. The duty is added to the net amount before the sales tax calculation.

You buy eight lamps that cost 25.00 each. The net amount for the invoice line is 200.00.

The gross amount for the invoice line is 200.00 + (8 x 5.00) = 240.00.

The tax is calculated as follows:

Total sales tax = 50 x 0.30 + 50 x 0.20 + 140 x 0.10 = 15 + 20 + 14 = 39.00

Total duty = 5.00 x 8 = 40.00

Total invoice amount = 200.00 + 39.00 + 40.00 = 279.00

**Variation**

If the invoice is created by using two invoice lines with four items on each line, the net amount per invoice line is 100.00.

The gross amount per invoice line would be 120.00, and the sales tax is created as follows:

Sales tax invoice line 1 = 50 x 0.30 + 50 x 0.20 + 20 x 0.10 = 15 + 10 + 2 = 27.00

Sales tax invoice line 2 = 50 x 0.30 + 50 x 0.20 + 20 x 0.10 = 15 + 10 + 2 = 27.00

Total sales tax = 27.00 + 27.00 = 54.00

Total duty = 5.00 x 8 = 40.00

Total invoice amount = 200.00 + 54.00 + 40.00 = 294.00

## Gross amount per unit

Select this option to calculate sales tax based on the value of the unit. This includes any other taxes.


> [!NOTE]
> <P>In a sales tax group, you can only have one sales tax code with this selection in the <STRONG>Marginal base</STRONG> field.</P>



## Example

The sales tax rates are set up in the following intervals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Amount</p></th>
<th><p>Tax rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0 - 50</p></td>
<td><p>30%</p></td>
</tr>
<tr class="even">
<td><p>50 - 100</p></td>
<td><p>20%</p></td>
</tr>
<tr class="odd">
<td><p>100 - 0 (&gt; 100)</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>


**Marginal base**: **Gross amount per unit**

There is a special duty of 5.00 on each lamp. The duty is added to the net amount before the sales tax calculation.

You buy eight lamps that cost 25.00 each. The gross amount per unit is 30.00.

The tax is calculated as follows:

Sales tax per unit = 30 x 30% = 9.00

Total sales tax = 9.00 x 8 = 72.00

Total duty = 5.00 x 8 = 40.00

Total invoice amount = 200.00 + 72.00 + 40.00 = 312.00

## Invoice total including other sales tax amounts

Select this option to calculate sales tax based on the total value for the invoice. This includes any other taxes.


> [!NOTE]
> <P>In a sales tax group, you can only have one sales tax code with this selection in the <STRONG>Marginal base</STRONG> field.</P>



## Example

The sales tax rates are set up in the following intervals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Amount</p></th>
<th><p>Tax rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0 - 50</p></td>
<td><p>30%</p></td>
</tr>
<tr class="even">
<td><p>50 - 100</p></td>
<td><p>20%</p></td>
</tr>
<tr class="odd">
<td><p>100 - 0 (&gt; 100)</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>


There is a special duty of 5.00 on each lamp. The duty is added to the net amount before the sales tax calculation.

You buy eight lamps that cost 25.00 each. The net amount for the invoice is 200.00.

The gross amount for the invoice is 200.00 + (8 x 5.00) = 240.00.

The tax is calculated as follows:

Total sales tax = 50 x 0.30 + 50 x 0.20 + 140 x 0.10 = 15 + 10 + 14 = 39.00

Total duty = 5.00 x 8 = 40.00

Total invoice amount = 200.00 + 39.00 + 40.00 = 279.00


> [!WARNING]
> <P>It makes no difference how many lines the invoice has, because the value in the <STRONG>Marginal base</STRONG> field is <STRONG>Invoice total incl. other sales tax amounts</STRONG>.</P>



## See also

[About the Whole amount and Interval options for sales tax codes](about-the-whole-amount-and-interval-options-for-sales-tax-codes.md)

  


