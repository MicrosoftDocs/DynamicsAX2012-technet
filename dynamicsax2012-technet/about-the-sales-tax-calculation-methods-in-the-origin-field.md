---
title: About the sales tax calculation methods in the Origin field
TOCTitle: About the sales tax calculation methods in the Origin field
ms:assetid: 267823d5-14e4-4cf4-af49-c9422ffda3ff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496823(v=AX.60)
ms:contentKeyID: 36056200
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- origin
- sales tax
- calculation method
- origin field
- sales tax calculation
- tax calculation method
---

# About the sales tax calculation methods in the Origin field 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

For each sales tax code that you create in the **Sales tax codes** form, you must select the method of calculation to apply to the tax base amount in the **Origin** field.

## Percentage of net amount

The **Percentage of net amount** calculation method is the default value in the **Origin** field. The sales tax is calculated as a percentage of the purchase or sale amount, excluding any other sales taxes.

## Example

The invoice line shows a quantity of 10 items at 1.00 each, and the customer is allowed a 10% line discount.

Net amount: 9.00

Sale tax: 25% x 9 = 2.25

Total amount: 9 + 2.25 = 11.25

## Percentage of gross amount

If you select the **Percentage of gross amount** method, the sales tax is calculated as a percentage of the gross sales amount, which in the following example includes all other sales taxes or duties.

## Example

The tax authority has imposed special duties on an item.

The duty amounts are added to the net amount before sales tax is calculated. You must set up the following sales tax codes:

  - Duty 1 = 10%, using the **Percentage of net amount** calculation method

  - Duty 2 = 20%, using the **Percentage of net amount** calculation method

  - Sales tax = 25%, using the **Percentage of gross amount** calculation method

If the net amount is 10.00, then Duty 1 is 1.00 (10.00 x 10%) and Duty 2 = 2.00 (10.00 x 20%).

The amounts would be as follows:

Gross amount: Net amount + Duty 1 amount + Duty 2 amount (10.00 + 1.00 + 2.00) = 13.00

Sales tax: 13.00 x 25% = 3.25

Total duties and sales tax: 1.00 + 2.00 + 3.25 = 6.25

Total amount: 10.00 + 6.25 = 16.25

## Percentage of gross amount, additional option

When you select **Percentage of gross amount** in the **Origin** field, you can also select a sales tax in the **Sales tax on sales tax** field.


> [!NOTE]
> <P>When you select a sales tax code in the <STRONG>Sales tax on sales tax</STRONG> field, only that sales tax is included in the gross amount for the sales tax calculation. If no sales tax code is selected in the <STRONG>Sales tax on sales tax</STRONG> field, the calculation includes all sales taxes in the gross amount for the sales tax calculation.</P>



1.  In the **Sales tax codes** form, select a sales tax code for which **Percentage of gross amount** is selected in the **Origin** field.

2.  On the **Calculation** tab, in the **Sales tax on sales tax** field, select a sales tax or duty to include in the gross amount in the sales tax calculation.

## Example

The tax authority has imposed special duties on an item.

One of the duty amounts must be added to the net amount before sales tax is calculated. You must set up the following sales tax codes:

  - Duty 1 = 10%, using the **Percentage of net amount** calculation method

  - Duty 2 = 20%, using the **Percentage of net amount** calculation method

  - Sales tax = 25%, using the **Percentage of gross amount** calculation method, with Duty 1 in the **Sales tax on sales tax** field

Net amount: 10.00

Duty 1: 10.00 x 10% = 1.00

Duty 2: 10.00 x 20% = 2.00

Gross amount: Net amount + Duty 1 amount (10.00 + 1.00) = 11.00

Sales tax: 11.00 x 25% = 2.75

Total duties and sales tax: 1.00 + 2.00 + 2.75 = 5.75

Total amount: 10.00 + 5.75 = 15.75

## Percentage of sales tax

When you select **Percentage of sales tax** in the **Origin** field, sales tax is calculated as a percentage of the sales tax that is selected in the **Sales tax on sales tax** field. The sales tax that is selected in the **Sales tax on sales tax** field is calculated first. The second sales tax is then calculated based on the first sales tax amount.

## Example

You must set up the following sales tax codes:

  - Duty 1 = 10%, using the **Percentage of net amount** method

  - Duty 2 = 20%, using the **Percentage of sales tax** method, with Duty 1 in the **Sales tax on sales tax** field

  - Sales tax = 25%, using the **Percentage of gross amount** method

Net amount: 10.00

Duty 1: 10.00 x 10% = 1.00

Duty 2: 1.00 x 20% = 0.20

Gross amount: 10.00 + 1.00 + 0.20 = 11.20

Sales tax: 11.20 x 25% = 2.80

Total sales tax: 1.00 + 0.20 + 2.80 = 4.00

Total amount: 10.00 + 4.00 = 14.00

## Amount per unit

When you select **Amount per unit** in the **Origin** field, sales tax is calculated as a fixed amount per unit. The unit is selected in the **Unit** field and the amount is specified in the **Values** form.

## Example

Sales tax is calculated as:

  - USD 1.00 per box

  - EUR 0.25 per kilo


> [!NOTE]
> <P>If the transaction is entered in another unit, it is converted automatically based on the unit conversions that are set up in the <STRONG>Unit conversions</STRONG> form.</P>



## Amount per unit, additional option

On the **Calculation** tab, you can select whether the duty is calculated before the sales tax. This determines whether the duty amount is included in the sales tax calculation.

  - Select **Percentage of gross amount** for the sales tax calculation and calculate a duty as an **Amount per unit** calculation. The duty amount is added to the net amount and is included in the gross amount in the sales tax calculation.

  - Select **Percentage of net amount** for the sales tax calculation and calculate a duty as an **Amount per unit** calculation. The duty amount is not added to the net amount and is excluded from the sales tax calculation.

  - Select **Percentage of net amount** for the sales tax calculation, calculate a duty as an **Amount per unit** calculation, and select the **Calculate before sales tax** check box on the **Calculation** tab for the duty calculation. The duty amount is added to the net amount and included in the calculation of sales tax.

## Examples

## Example 1

Duty 1: 5.00

**Origin** field value: **Amount per unit**

Sales tax: 25%, using the **Percentage of gross amount** method

The **Calculate before sales tax** check box has no effect, because sales tax is calculated as a percentage of the gross amount.

Net amount: 10.00

Duty 1: 1 x 5.00 = 5.00

Gross amount: 10.00 + 5.00 = 15.00

Sales tax: 15.00 x 25% = 3.75

Total sales tax: 5.00 + 3.75 = 8.75

Total amount: 10.00 + 8.75 = 18.75

## Example 2

Duty 1: 5.00

**Origin** field value: **Amount per unit**

Sales tax: 25%, using the **Percentage of net amount** method

The **Calculate before sales tax** check box is not selected for the duty calculation.

Net amount: 10.00

Duty 1: 1 x 5.00 = 5.00

Sales tax: 10.00 x 25% = 2.50

Total sales tax: 5.00 + 2.50 = 7.50

Total amount: 10.00 + 7.50 = 17.50

## Example 3

Duty 1: 5.00

**Origin** field value = **Amount per unit**

Sales tax: 25%, using the **Percentage of net amount** method

The **Calculate before sales tax** check box is selected for the duty calculation.

Net amount: 10.00

Duty 1: 1 x 5.00 = 5.00

Sales tax: (10.00 + 5.00) x 25% = 3.75

Total sales tax: 5.00 + 3.75 = 8.75

Total amount: 10.00 + 8.75 = 18.75

## Example 4

The result of Example 3 and Example 1 is the same, because there is only one duty.

Assume that you have two duties, and only one of them is included in the net amount for the sales tax calculation:

Duty 1: 5.00, using the **Amount per unit** method, and the **Calculate before sales tax** check box is selected

Duty 2: 2.50, using the **Amount per unit** method, and the **Calculate before sales tax** check box is not selected

Sales tax: 25%, using the **Percentage of net amount** method

Net amount: 10.00

Duty 1: 1 x 5.00 = 5.00

Duty 2: 1 x 2.50 = 2.50

Net amount subject to sales tax: 10.00 + 5.00 = 15.00

Sales tax: 15.00 x 25% = 3.75

Total sales taxes, including duties: 5.00 + 2.50 + 3.75 = 11.25

Total amount: 10.00 + 11.25 = 21.25

The 25 percent sales tax is calculated for the sum of the net amount (10.00) + Duty 1 (5.00) = 15.00. Duty 2 is added to the tax amount after the sales tax is calculated.

## Calculated percentage of net amount

The **Calculated percentage of net amount** calculation method is used in Germany.

## Example

Net amount: 10.00

Tax rate: 25%

Sales tax: Net amount x tax rate (10.00 x 25%) = 2.50

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

