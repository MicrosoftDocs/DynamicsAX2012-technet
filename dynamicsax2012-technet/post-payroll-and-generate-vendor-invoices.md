---
title: Post payroll and generate vendor invoices
TOCTitle: Post payroll and generate vendor invoices
ms:assetid: c3c9d2e3-c947-497a-a6a2-317bb27e779a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677360(v=AX.60)
ms:contentKeyID: 49384135
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- Classes.PayrollIssueWorkerPayProcess
- Classes.PayrollPayStatementGenerateVendorInvoice
- Classes.PayrollPayStatementPost
- worker payments
- payroll posting
- payroll vendor
- payroll vendors
- payroll vendor invoices
audience: Application User
ms.search.region: USA
---

# Post payroll and generate vendor invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to post payroll and generate the required vendor invoices.

When you post payroll, the accounting distributions that are specified on each pay statement line determine the offset accounts to use. When each line has a balanced transaction, all transactions for the pay statement can be entered in the general ledger.


> [!NOTE]
> <P>Offset accounts are determined by the posting definitions that are assigned to pay statements in the <STRONG>Transaction posting definitions</STRONG> form. When you post a pay statement, all lines must be successfully posted or no lines are posted. Similarly, when you post multiple pay statements and one fails, no pay statements are posted.</P>



After you post payroll, you should generate vendor invoices for the payables that resulted from the pay period that you posted. This process combines the amounts from all the pay statements that were posted for the period and uses the benefit and tax setup information to create an invoice for each vendor. The totals and their corresponding accounting distributions from the original pay statement lines are used to create the invoices.

## What do you want to do?

This task is part of a bigger process

Prerequisites

Post pay statements and generate vendor invoices for a single pay period

Post a pay statement for an individual worker and submit it for payment

Generate vendor invoices for a specific benefit plan

Generate multiple invoices for the same vendor

Technical information for system administrators

## This task is part of a bigger process

This illustration shows how this topic fits into the larger picture of payroll processing.

For an overview of the process, see [Processing payroll](processing-payroll.md).

![Basic steps for processing earnings](images/JJ677320.Payroll_Processing_earnings_basics(AX.60).gif "Basic steps for processing earnings")

Back to top

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
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3 Cumulative Update 8</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
<tr class="odd">
<td><p>Related configuration tasks</p></td>
<td><p>You must complete these tasks before you can post payroll and generate vendor invoices:</p>
<ul>
<li><p>Set the <strong>Payroll clearing account</strong> field in the <strong>Payroll parameters</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677433(v=ax.60)">Payroll parameters (form)</a>.</p></li>
<li><p>Set the <strong>Procurement category</strong> field in the <strong>Payroll parameters</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677433(v=ax.60)">Payroll parameters (form)</a></p></li>
<li><p>Make sure that transaction posting definitions are created for payroll. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh242550(v=ax.60)">Transaction posting definitions (form)</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Post pay statements and generate vendor invoices for a single pay period

After you review pay statement for a specific pay period, you post the pay statements to the general ledger and generate vendor invoices for the same pay period.


> [!TIP]
> <P>Any pay statements that must be recalculated are ignored by the posting process. Therefore, we recommend that you view the <STRONG>Pay statements to recalculate</STRONG> list page to verify that no pay statements must be recalculated before you complete this process. For more information, see “Modify pay statements” in <A href="work-with-pay-statements.md">Work with pay statements</A>.</P>



To post pay statements and generate vendor invoices for a pay period, follow these steps:

1.  Post the pay statements:
    
      - Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Post pay statements**.
    
      - In the **Pay cycle** field, select the pay cycle to post pay statements for.
    
      - In the **Pay period** field, select the pay period to post pay statements for. The pay periods that are displayed are available for the pay cycle. The default pay period is the first open pay period, but you can select any open pay period from the list.
    
      - Click **OK**.

2.  Generate the vendor invoices:
    
      - Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Generate vendor invoices**.
    
      - In the **Pay cycle** field, select the pay cycle to generate vendor invoices for.
    
      - In the **Pay period** field, select the same pay period that you posted the pay statements for.
    
      - Select **All invoices**.
    
      - Click **OK**. You can’t delete or recalculate the invoices.

3.  Double-click the pay statement to open the **Pay statement** detail form, and then verify this information:
    
      - If the pay statement was posted successfully, **Posted** is displayed in the pay statement header.
    
      - If the vendor invoice was generated successfully, the check box in the **Included in invoice** column is selected on some pay statement lines.

Back to top

## Post a pay statement for an individual worker and submit it for payment

To post a pay statement for a specific worker to the general ledger and submit it for payment, follow these steps:

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Select the pay statement for the specific worker and pay period.

3.  On the **Financials** tab, in the **Accounting** group, click **Post**.

4.  Select the **Submit for payment after posting** check box. For more information about this check box, see [Issue worker payments](issue-worker-payments.md).

5.  In the **Post the selected pay statement** form, click **Post**. A message is displayed to indicate that the pay statement was posted successfully. You can’t delete or recalculate the invoice.
    

    > [!TIP]
    > <P>To verify that the pay statement was posted, double-click the pay statement to open the <STRONG>Pay statement</STRONG> detail form. <STRONG>Posted</STRONG> is displayed in the pay statement header.</P>



Back to top

## Generate vendor invoices for a specific benefit plan

After pay statements for a specific cycle and pay period are posted to the general ledger, you generate vendor invoices for a specific benefit plan for the pay period. To do so, follow these steps:

1.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Generate vendor invoices**.

2.  In the **Pay cycle** field, select the pay cycle to generate vendor invoices for.

3.  In the **Pay period** field, select the pay period to post pay statements for. The pay periods that are displayed are available for the pay cycle. The default pay period is the first open pay period, but you can select any open pay period from the list.

4.  Select **Benefit plan invoice** and select the benefit plan to generate invoices for.

5.  Click **OK**.

6.  To verify that at least one vendor invoice was generated, double-click the pay statement to open the **Pay statement** detail form. A check mark appears in the **Included in invoice** column of the benefit plan statement line.
    
    You can also verify that a new vendor invoice was created and posted for the vendor.

Back to top

## Generate multiple invoices for the same vendor

After pay statements for a specific pay cycle and pay period have been posted to the general ledger, you generate all the vendor invoices for a specific vendor. These include multiple invoices for several benefit plans.

To generate multiple invoices for one vendor, follow these steps:

1.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Generate vendor invoices**.

2.  In the **Pay cycle** field, select the pay cycle to generate vendor invoices for.

3.  In the **Pay period** field, select the pay period to post pay statements for. The pay periods that are displayed are available for the pay cycle. The default pay period is the first open pay period, but you can select any open pay period from the list.

4.  Select **Vendor invoice** and select the vendor to generate invoices for.

5.  Click **OK**.

6.  To verify that the vendor invoice was generated, double-click the pay statement to open the **Pay statement** detail form. Verify that the pay statement lines for the benefits that are associated with the vendor have a check mark in the **Included in invoice** column.
    
    You can also verify that at least one vendor invoice was created for the vendor.

Back to top

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
<td><p><strong>Payroll - USA</strong></p>
<div class="alert">

> [!IMPORTANT]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To post payroll and generate vendor invoices, you must be a member of a security role that includes this duty:</p>
<ul>
<li><p>Post pay statements (PayrollJournalizePayStatementMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To post payroll and generate vendor invoices, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p>View budget check errors or warnings inquiry (BudgetCheckResultsView)</p></li>
<li><p>Create vendor invoices for payroll (PayrollGenerateVendorInvoice)</p></li>
<li><p>Process payroll posting (PayrollJournalizePayStatement)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

  


