---
title: Customer account statement report (CustAccountStatementExt)
TOCTitle: Customer account statement report (CustAccountStatementExt)
ms:assetid: 6c518898-5f14-4075-84df-59abea19f096
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa615057(v=AX.60)
ms:contentKeyID: 36059153
ms.date: 08/18/2014
mtps_version: v=AX.60
f1_keywords:
- Menu_items.output.CustAccountStatementExt
- SSRS_Reports.Reports.CustAccountStatementExt
---

# Customer account statement report (CustAccountStatementExt) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Customer account statement** report displays external customer account statements that you can send to your customers.

The currency and language for the customer are used on the external account statement. This differs from the internal customer account statement, which always displays amounts in the accounting currency for the legal entity. If the account statement includes transactions for more than one currency, the opening balance and the closing balance are displayed in each currency.

To improve performance when you run statements for many customers at the same time, use one or more of the following options:

  - Use batch processing. By moving the processing to a server, report performance can improve.

  - Use parallel processing. By dividing this process into multiple tasks, report performance can improve. Because multiple tasks are running at the same time, the reports might be printed in a different order than the order that was specified.

  - Apply range restrictions to limit the number of records in each batch. Performance can be improved by submitting multiple smaller batches to be processed at the same time on different servers, instead of submitting one large batch.

  - You can select the **Only open** check box to include only open transactions, instead of all transactions, for each customer.

  - You can select the **Balance other than zero** check box to avoid printing statements for customers who have a balance of 0.00.

If your organization uses centralized statements, which means sending customer statements from one legal entity on behalf of other legal entities in your organization, make sure that you are using the legal entity of the statement before you print statements. Information about a customer's account activity in other legal entities is included on the statement, if the legal entities use the same party ID for that customer account. The transactions for each legal entity will be grouped together on the statement.

The statement address that is specified for the customer account is included on the statement. If a statement address is not specified, the primary address for the customer account is used.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Use print management destination</strong></p></td>
<td><p>Select this check box to print the customer statement original and copies to the printer destination that is specified for the module or customer.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date of the transactions to include on the statement. By default, the report displays the opening balance in each currency for which transactions exist, as of the date in the <strong>From date</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the transactions to include on the statement. By default, the report displays the closing balance in each currency for which transactions exist, as of the date in the <strong>To date</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Only open</strong></p></td>
<td><p>Select this check box to include only transactions that are not settled. This option helps reduce the time that is required to generate statements, because the reports include only open transactions, instead of all transactions, for each customer.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include reversed</strong></p></td>
<td><p>Select this check box to include reversed transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Associated payment attachment on interest note</strong></p></td>
<td><p>Select the type of giro money transfer slip to print, or select <strong>None</strong>. If you are printing centralized statements, a giro money transfer slip is printed only if the currency code of all the transactions printed on the statement is the same as the accounting currency of the statement legal entity.</p>
<div class="alert">

> [!TIP]
> <P>To be able to select one type of giro money transfer slip at a time in the <STRONG>Criteria</STRONG> column, click the <STRONG>Select</STRONG> button, and on the <STRONG>Range</STRONG> tab, select <STRONG>Associated payment attachment on interest note</STRONG> in the <STRONG>Field</STRONG> column.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Giro with sum</strong></p></td>
<td><p>Select this check box to print the giro money transfer slip that is selected in the <strong>On an account statement</strong> field on the <strong>Invoice and delivery</strong> tab in the <strong>Customers</strong> form. The amount is printed on the giro money transfer slip only if this check box is selected and the accounting currency is used.</p></td>
</tr>
<tr class="even">
<td><p><strong>Balance other than zero</strong></p></td>
<td><p>Select this check box to exclude statements that have a closing balance of zero. This option helps reduce the time that is required to generate statements, because statements are not generated for customers who have a balance of 0.00.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show payment schedule</strong></p></td>
<td><p>Select this check box to print the payment schedule installments in detail.</p>
<p>If this check box is cleared and a payment schedule exists, <strong>Multiple</strong> is shown as the due date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show credit limit</strong></p></td>
<td><p>This check box is selected if a credit limit has been assigned to a customer.</p>
<div class="alert">

> [!NOTE]
> <P>The credit limit is always in the accounting currency and is shown on a customer statement only if the customer currency is the same as the accounting currency.</P>


</div>
<p>The available credit for the customer, which is calculated after the closing balance, is also included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show due until</strong></p></td>
<td><p>Select a date to include information about transactions that are due as of that date, in a separate section of the statement. For example, you can use this to include the amount, transactions, and date due for the next payment on the statement.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show maturity distribution</strong></p></td>
<td><p>Select this check box to print the maturity distribution at the bottom of the statement.</p>
<p>You can select this check box only if you have entered dates in the <strong>From date</strong> and <strong>To date</strong> fields. Amounts are included in the maturity distributions based on the due date for each transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Aging period definitions</strong></p></td>
<td><p>Select this option to show the maturity distribution according to aging period definitions that have been specified for your legal entity.</p></td>
</tr>
<tr class="even">
<td><p><strong>Aging period definition</strong></p></td>
<td><p>Select an aging period definition. Aging period definitions that have more than six columns (aging periods) are not available in the selection list and cannot be included on a printed statement.</p>
<p>This field is available only if you selected the <strong>Aging period definitions</strong> option.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print period description</strong></p></td>
<td><p>Select <strong>Yes</strong> to include aging period descriptions at the top of each aging period column on the report.</p>
<p>This field is available only if you selected the <strong>Aging period definitions</strong> option.</p></td>
</tr>
<tr class="even">
<td><p><strong>Manual setup of maturity distribution</strong></p></td>
<td><p>Select this option to show the maturity distribution according to period intervals that you define.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Interval</strong></p></td>
<td><p>Define the period to use by entering the number of the day or month units in each period that is selected in the <strong>Day/Mth</strong> field. For example, to view aging information by week, enter 7 in this field and select <strong>Day</strong> in the <strong>Day/Mth</strong> field.</p>
<p>This field is available only if you selected the <strong>Manual setup of maturity distribution</strong> option.</p></td>
</tr>
<tr class="even">
<td><p><strong>Day/Mth</strong></p></td>
<td><p>Select the unit, either <strong>Day</strong> or <strong>Month</strong>, that is used to define the period in the <strong>Interval</strong> field.</p>
<p>This field is available only if you selected the <strong>Manual setup of maturity distribution</strong> option.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Printing direction</strong></p></td>
<td><p>Select whether to print summarized information for past or future periods, with regard to the date that is selected in the <strong>To date</strong> field. Select <strong>Backward</strong> to show information for past periods. Select <strong>Forward</strong> to show information for future periods.</p>
<p>This field is available only if you selected the <strong>Manual setup of maturity distribution</strong> option.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customers</strong></p></td>
<td><p>The information displayed in this field group is determined by your selections when you create a query.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>CustAccountStatementExt</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustAccountStatementExt</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustAccountStatementExt</p>
<p>CustAccountStatementExtAction</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Customer account statement</strong>.</p>
<p>Click <strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Customers</strong> &gt; <strong>All customers</strong>. On the <strong>Action Pane</strong>, on the <strong>Collect</strong> tab, click <strong>Statements</strong>.</p>
<p>Click <strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Collections</strong> &gt; <strong>Collections</strong>. On the <strong>Action Pane</strong>, on the <strong>Communicate</strong> tab, click <strong>Statements</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustTable table

  - CustAccountStatementExtTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the CustAccountStatementExtDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Print periodic customer account statements](print-periodic-customer-account-statements.md)

[Set up print management for a module](set-up-print-management-for-a-module.md)

[Print management setup (form)](https://technet.microsoft.com/en-us/library/hh209383\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

