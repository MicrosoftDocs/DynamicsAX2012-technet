---
title: Set up conditional sales taxes
TOCTitle: Set up conditional sales taxes
ms:assetid: 138f044a-9262-4577-9fe0-583e221e3776
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496600(v=AX.60)
ms:contentKeyID: 36676369
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up conditional sales taxes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sales taxes are usually reported in the period when the invoice is created.

However, if a sales tax authority allows for sales taxes and base amounts to be reported when the invoice is paid, you can use the conditional sales taxes functionality. For invoices that are not fully settled with a single payment, sales taxes are reported and paid to the sales tax authority on the amounts that are settled, not on the total invoice amount.

## Example

On June 10, you create an invoice of 10,000 plus 2,500 in sales tax.

On July 10, you report taxes for June. The 2,500 is not included in the sales tax payment, because the invoice has not been paid.

On July 15, the customer pays half of the invoice amount, 5,000, plus 1,250 in sales tax.

On August 10, you report taxes for July. The 1,250 is included in the sales tax payment.

When the customer settles the invoice with a second payment of 6,250, the remaining sales taxes are reported and paid.

## Overview of how to set up conditional sales taxes

1.  Required in some countries/regions: Create separate main accounts for sales taxes on invoices that are awaiting settlement, and create separate sales tax ledger posting groups to control the posting of conditional sales taxes to the separate main accounts.

2.  Create a separate settlement period for conditional sales taxes that is aligned with the settlement period for ordinary sales taxes and for reporting to the sales tax authority.

3.  Create and align two sales tax codes: one for the conditional sales tax and one for the sales taxes that you have to report.

4.  Set up sales tax groups and item sales tax groups that contain one of the two sales tax codes that you created.

5.  Select the **Conditional sales tax** check box in the **Sales tax** area of the **General ledger parameters** form.

## 1\. Create main accounts and ledger posting groups

In many countries/regions, you are required by law to separate conditional sales taxes from taxes that are reported and paid at the time of invoicing.

If there is no such requirement, you can post conditional sales taxes to the same main accounts as other sales taxes.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

2.  Select a chart of accounts.

3.  On the **Main accounts** FastTab, click **New** to create a main account.

4.  Enter the main account number.

5.  Enter a name, such as Sales tax awaiting settlement.

6.  In the **Main account type** field, select **Balance sheet**.

7.  On the **Setup** FastTab, in the **Posting type** field, select **Sales tax**.

8.  Create a separate ledger posting group to control the postings to the main account for conditional sales taxes. Click **General ledger** \> **Setup** \> **Sales tax** \> **Ledger posting groups**. Create a ledger posting group where you specify the main accounts that are used for conditional taxes. For more information, see [Set up ledger posting groups for sales tax](set-up-ledger-posting-groups-for-sales-tax.md).

## 2\. Create a separate settlement period for conditional sales taxes

To track conditional sales taxes, you must create a settlement period that is used only for this purpose. Conditional sales taxes are then reported and paid correctly to the sales tax authority. You can also generate a report that shows conditional sales tax amounts that have not yet been reported to tax authorities.

For more information about how to set up a settlement period, see [Set up a sales tax settlement period](set-up-a-sales-tax-settlement-period.md).


> [!NOTE]
> <P>You must also set up a settlement period for sales taxes that are not conditional sales taxes, and for paying the sales tax authority to which you report the conditional sales taxes. The period interval must be the same for both settlement periods, such as three months, and you must set up the same periods in each settlement period.</P>



## 3\. Create and align sales tax codes for conditional sales taxes

Two sales tax codes must be created for the conditional sales tax functionality.

  - One sales tax code for posting ordinary sales taxes and for reporting and paying all sales taxes to the sales tax authorities.

  - One sales tax code for calculating and posting the conditional sales tax. When the conditional sales tax amounts are posted, they are transferred to the reporting sales tax code.

## Create a sales tax code for reporting to the sales tax authorities

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New** to create a code.

3.  Enter a unique identifier or code.

4.  Enter a name or description.

5.  In the **Settlement period** field, select the settlement period that is used for reporting taxes to the sales tax authority.

6.  In the **Ledger posting group** field, select the ledger posting group that is used for the ordinary sales taxes that are reported to the sales tax authority.

7.  Click **Values**, and enter the tax rate of the tax code in the **Value** field.

## Create a sales tax code for conditional tax

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New** to create a code.

3.  Enter a unique identifier or code.

4.  Enter a name or description.

5.  In the **Settlement period** field, select the settlement period that is used for conditional tax.

6.  In the **Ledger posting group** field, select the ledger posting group that is used for conditional tax.

7.  In the **Payment sales tax code** field, select the sales tax code for reporting to the sales taxes tax authority.
    

    > [!NOTE]
    > <P>When you post the conditional sales tax for the conditional tax settlement period, the amount to be paid is transferred to the sales tax code that you select here.</P>



8.  Click **Values**, and enter the tax rate of the tax code in the **Value** field.

## 4\. Create sales tax groups and item sales tax groups for conditional sales taxes

1.  Create the sales tax groups and item sales tax groups that are used on invoices for which conditional taxes are calculated.

2.  Add one of the sales tax codes that you created in this procedure to the sales tax groups and to the item sales tax groups that are used for conditional taxes. For more information, see [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md) and [Create item sales tax groups](create-item-sales-tax-groups.md).

## 5\. Enable the conditional tax functionality

Select the **Conditional sales tax** check box in the **Sales tax** area of the **General ledger parameters** form.

When this check box is selected, sales tax amounts are transferred from the main account for temporary postings of conditional taxes to the sales tax payment account.

**Example**

You create a sales order of 10 lamps for customer 4008, The Warehouse. The total invoice amount is 100.00 plus sales tax.

The customer is linked to the Normal sales tax group, which includes the C25% sales tax code.

The item is linked to the Full item sales tax group, which includes the C25% sales tax code.

When you post the customer invoice, sales taxes of 25.00 are calculated. The sales tax amount is posted on the main account that is specified as the ledger posting group for conditional taxes.

If you print a sales tax payment report for the settlement period for ordinary sales taxes, the 25.00 is not included on the report.

If you print a sales tax payment report for the settlement period for conditional taxes, the 25.00 is included on the report.

When you post the payment from the customer, a sales tax transaction is created that offsets the temporary posting on the main account for conditional taxes. Another transaction is created on the reporting or ordinary sales tax account that has the amount to be paid to the tax authority.

The next time that you print a sales tax payment report for the settlement period for reporting or ordinary sales taxes, the 25.00 is included on the report.

  


