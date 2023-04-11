---
title: (FIN) Set up and generate the Finnish sales tax report in a foreign currency
TOCTitle: (FIN) Set up and generate the Finnish sales tax report in a foreign currency
ms:assetid: ae40ede6-a338-4a72-93ae-3af1360b5436
ms:mtpsurl: https://technet.microsoft.com/library/Dn511004(v=AX.60)
ms:contentKeyID: 59953757
author: tonyafehr
ms.date: 04/28/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax reports
- Classes.TaxReport
- payment report
- Forms.TaxAuthority
- Forms.TaxTable
- SSRS_Reports.Reports.TaxReport_FI
- Finland
- Forms.TaxReportCollection
- sales tax report
- sales tax payment
- FI - 00012
- payment reports
- sales tax payments
audience: Application User
ms.search.region: Finland
---

# (FIN) Set up and generate the Finnish sales tax report in a foreign currency 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a foreign currency for a sales tax code, and then generate the sales tax report in the foreign currency. Alternatively, you can generate the sales tax report in a foreign currency that you specify in the **Finnish sales tax report** form.

You can generate the Finnish sales tax report in a foreign currency in the following scenarios:

  - When the currency of the legal entity is different from the currency of the country where the legal entity is based, you can generate the sales tax report in the currency of the country where the legal entity is based.

  - When the currency of the legal entity is the same as that of the country where the legal entity is based, but the legal entity must generate sales tax reports in the currency of another country, you can generate the sales tax report in the currency of that country. For example, a legal entity that is a global firm that has subsidiaries in other countries, and which uses a primary currency for all of the subsidiaries, can generate the sales tax report in the currency of the country where a subsidiary is based instead of the primary currency of the legal entity.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Finland</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up a sales tax settlement period. For more information, see <a href="set-up-a-sales-tax-settlement-period.md">Set up a sales tax settlement period</a>.</p></li>
<li><p>Set up a sales tax code. For more information, see <a href="create-various-kinds-of-sales-tax-codes.md">Create various kinds of sales tax codes</a>.</p></li>
<li><p>Set up an item sales tax group. For more information, see <a href="create-item-sales-tax-groups.md">Create item sales tax groups</a>.</p></li>
<li><p>Set up a sales tax group. For more information, see <a href="set-up-and-use-a-sales-tax-group.md">Set up and use a sales tax group</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a sales tax authority for the Finnish sales tax report

Use the **Sales tax authorities** form to set up a sales tax authority that uses the Finnish report layout.

To perform this task, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax authorities**.

2.  Create a sales tax authority to pay sales tax to. For more information, see [Set up sales tax authorities](set-up-sales-tax-authorities.md).

3.  On the **General** FastTab, in the **Report layout** field, select **Finnish report layout**.

## 2\. Set up a sales tax reporting code for the Finnish sales tax report

Use the **Sales tax reporting codes** form to set up a sales tax reporting code that uses the Finnish report layout.

To perform this task, follow these steps:

1.  Click **General ledger** \> **Reports** \> **Base data** \> **Various** \> **Sales tax reporting codes**.

2.  Click **New** or press CTRL+N to create a sales tax reporting code.

3.  In the **Report layout** field, select **Finnish report layout**.

4.  In the **Reporting code** field, enter a reporting code that corresponds with a field number in the sales tax report. You can select field numbers on the **Report setup** FastTab in the **Sales tax codes** form to indicate the sections on the sales tax report where the sales information, purchase information, or import information is printed.

5.  Enter report text and a brief description for the reporting code, if required. For more information, see [Sales tax reporting codes (form)](https://technet.microsoft.com/library/aa588316\(v=ax.60\)).

## 3\. Set up a foreign currency for a sales tax code

Use the **Sales tax codes** form to set up a foreign currency for a sales tax code. You can use this sales tax code to generate the Finnish sales tax report in the foreign currency.

To perform this task, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Select a sales tax code.

3.  On the **General** FastTab, in the **Currency** field, select the foreign currency to use to generate the Finnish sales tax report.

## 4\. Calculate sales tax and generate the Finnish sales tax report

Use the **Sales tax payment** form to calculate sales tax that is due for a given period. You can then use the **Finnish sales tax report** form to generate the Finnish sales tax report in a foreign currency.


> [!NOTE]
> <P>Ensure that you have created and posted vendor payment journals using the sales tax information that you set up. For more information, see <A href="https://technet.microsoft.com/library/aa557917(v=ax.60)">Journal header (form)</A>, <A href="https://technet.microsoft.com/library/aa616218(v=ax.60)">Journal voucher - Invoice journal (form)</A>, and <A href="post-invoices-in-an-invoice-journal.md">Post invoices in an invoice journal</A>.</P>



To perform this task, follow these steps:

1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.

2.  Specify the criteria, such as settlement period, transaction date, and sales tax payment version for sales tax calculation, and then click **OK** to run the calculation. For more information, see [Sales tax payment (class form)](https://technet.microsoft.com/library/aa598539\(v=ax.60\)).

3.  In the **Finnish sales tax report** form, in the **Tax currency** field, select the currency that determines which transactions to include in the report. The transactions that are generated using the tax currency and the transactions that are generated using the tax codes that use the tax currency are included in the report.

4.  In the **Reporting currency** field, select the foreign currency in which the report is generated.
    

    > [!NOTE]
    > <P>If the reporting currency is different from the tax currency, and if you select the <STRONG>Currency rate on reporting date</STRONG> check box, the currency rate on the reporting date that you specify in the <STRONG>Reporting date</STRONG> field is used for all of the transactions in the report. Alternatively, if the reporting currency is different from the tax currency, and if you clear the <STRONG>Currency rate on reporting date</STRONG> check box, the currency rate on the transaction date is used for all of the transactions in the report.</P>



5.  Select the **Currency rate on reporting date** check box to indicate that the currency rate on the reporting date is used for all of the transactions.

6.  In the **Reporting date** field, select the date when the report is generated.
    

    > [!NOTE]
    > <P>This field is available only if you select the <STRONG>Currency rate on reporting date</STRONG> check box.</P>



7.  Click **OK** to generate the Finnish sales tax report.

## Related tasks

[(FIN) Finnish sales tax report (TaxReport\_FI)](fin-finnish-sales-tax-report-taxreport-fi.md)

[(FIN) Generate a Finnish Intrastat declaration](fin-generate-a-finnish-intrastat-declaration.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

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
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Ensure that the <strong>LedgerBasicSalesTax</strong> configuration key is available under the <strong>Data Dictionary</strong> &gt; <strong>Configuration Keys</strong> node in the Application Object Tree.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the <strong>Maintain sales tax transactions</strong> (TaxSalesTaxTransactionsMaintain) duty.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the <strong>Settle sales taxes due</strong> (TaxReportProcess privilege) privilege.</p></td>
</tr>
</tbody>
</table>

  


