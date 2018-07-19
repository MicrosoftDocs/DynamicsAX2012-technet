---
title: (HUN) Set up and generate an itemized VAT statement
TOCTitle: (HUN) Set up and generate an itemized VAT statement
ms:assetid: 736eca2a-c207-4e0c-84a6-de4b51cb439c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn268481(v=AX.60)
ms:contentKeyID: 54917020
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Report
- Forms.LedgerParameters
- Forms.TaxPeriod
- VAT
- Forms.TaxReporting_W
- MsDynAx060.Forms.LedgerParameters
- MsDynAx060.Forms.TaxReporting_W
- MsDynAx060.Forms.TaxPeriod
- Itemized VAT
- Value added tax
- VAT reporting
audience: Application User
ms.search.region: Hungary
---

# (HUN) Set up and generate an itemized VAT statement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Legal entities or individuals that are liable to pay value-added tax (VAT) for the acquisition or supply of items or services can use Microsoft Dynamics AX to set up and generate an itemized VAT statement. This statement contains details about the completed VAT transactions and can be generated for individual invoices.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Currency setup</p></td>
<td><p>Specify a currency exchange rate so that your company can receive or make payments in foreign currencies. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh209477(v=ax.60)">Currency exchange rates (form)</a>.</p>
<p>You can also set up a reporting currency in the <strong>Ledger</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh209331(v=ax.60)">Ledger (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Sales tax setup</p></td>
<td><p>Ensure that you have specified the settings that are required to calculate sales tax for your transactions. You can specify the following settings for sales tax:</p>
<ul>
<li><p>Sales tax codes. For more information, see <a href="set-up-and-use-sales-tax-codes.md">Set up and use sales tax codes</a>.</p></li>
<li><p>Sales tax groups. For more information, see <a href="set-up-and-use-a-sales-tax-group.md">Set up and use a sales tax group</a>.</p></li>
<li><p>Item sales tax groups. For more information, see <a href="create-item-sales-tax-groups.md">Create item sales tax groups</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Configure settings to generate itemized VAT statements

Before you can generate an itemized VAT statement, you will need to enable Microsoft Dynamics AX to do so. You can begin by setting up parameters in the **General ledger parameters** form.

To configure the settings to generate itemized VAT statements, follow these steps:

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the **General ledger parameters** form, in the **Sales tax** area, on the **VAT statement** FastTab, select the **Enable to print itemized VAT statement** check box.

3.  In the **Itemized VAT statement limit (HUF)** field, enter an amount limit, in Hungarian Forints, that determines which invoice transactions are included on the itemized VAT statement. An invoice with a total amount that exceeds this value requires an itemized VAT statement.

## 2\. Define a settlement period for VAT reporting

You can define a settlement period that determines which invoice transactions are included on the itemized VAT statement. You can customize your settlement period based on your company’s requirements for VAT reporting.

To define a settlement period for VAT reporting, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax settlement periods**.

2.  On the **General** FastTab, in the **Period interval** field, select the unit to use to specify the duration of the settlement period.

3.  In the **Number of units** field, enter the number of units for the period that you want to report.

4.  On the **Periods** FastTab, click **Add**.

5.  In the **From date** and **To date** fields, enter the starting date and ending date of the settlement period.

For more information about defining a settlement period, see [Set up a sales tax settlement period](set-up-a-sales-tax-settlement-period.md).

## 3\. Generate and export the itemized VAT statement

You can now generate the itemized VAT statement. After you generate the statement, you can verify the items, print the report, and then export the report file for processing.

To generate and export the itemized VAT statement, follow these steps:

1.  Click **General ledger** \> **Periodic** \> **VAT reporting**.

2.  In the **Date** field, enter the date to display the itemized VAT details for the specified settlement period.

3.  In the **Settlement period** field, enter the settlement period that you want to generate the report for.

4.  Click **Create report**.

5.  In the **Sales tax declaration information** form, in the **Run mode** field, select **Amounts in company currency for accounting** to print the itemized VAT statement.

6.  Select the **Generate file** check box to indicate that you want to create an export file for the itemized VAT statement.

7.  In the **File name** field, enter the file name and path to save the export file, and then click **OK**.

8.  After you save the export file, click **Print report**.

9.  In the **Sales tax declaration information** form, click **OK**. The report is printed and exported.

## Related tasks

[(HUN) Create and post a sales order invoice with a specific VAT register date](hun-create-and-post-a-sales-order-invoice-with-a-specific-vat-register-date.md)

[(HUN) Create and post a purchase order invoice with a specific VAT register date](hun-create-and-post-a-purchase-order-invoice-with-a-specific-vat-register-date.md)

[Sales tax settlement periods (form)](https://technet.microsoft.com/en-us/library/aa633944\(v=ax.60\))

[(HUN) VAT reporting (form)](https://technet.microsoft.com/en-us/library/jj664308\(v=ax.60\))

  


