---
title: Work with pay statements
TOCTitle: Work with pay statements
ms:assetid: 1d338991-a441-4556-9538-82f94393a181
ms:mtpsurl: https://technet.microsoft.com/library/JJ677329(v=AX.60)
ms:contentKeyID: 49384103
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- Classes.PayrollPayStatementGeneration
- pay statement
- pay statements
audience: Application User
ms.search.region: USA
---

# Work with pay statements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes the process that you use to generate pay statements, as well as other tasks, such as reversing a pay statement, that you might need to do after you generate pay statements.

When you generate pay statements, all worker deductions and employer contributions for benefits and taxes are calculated, benefit accruals are processed, and the worker’s net pay is determined.

When you generate pay statements, we recommend that you use the batch processing mode to improve performance.

Completed pay statements are used to issue worker payments. For more information, see [Issue worker payments](issue-worker-payments.md).

## What do you want to do?

This task is part of a bigger process

Prerequisites

Generate pay statements

Delete pay statements

Modify earning lines on pay statements

Modify benefit lines and tax lines on pay statements

Modify benefit accrual lines on pay statements

Reverse a pay statement

Technical information for system administrators

Find related tasks

## This task is part of a bigger process

This illustration shows where generating pay statements fits into the larger picture of payroll processing. Other tasks that are described in this topic are not part of the end-to-end payroll process.

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
<td><p>Make sure that the following parameters are set up in the <strong>Payroll parameters</strong> form:</p>
<ul>
<li><p>In the <strong>Calculation settings</strong> area, the <strong>Accounting date options for earnings</strong> field, the <strong>Include dimensions on deduction calculations</strong> check box, and the <strong>Payroll clearing account</strong> field. If your organization recovers arrears, also complete the <strong>Recover arrears in all payment run types</strong> check box and the <strong>Arrear threshold</strong> field.</p></li>
<li><p>In the <strong>Payment issuance</strong> area, the methods of payment for check and electronic payments.</p></li>
<li><p>In the <strong>Number sequences</strong> area, the number sequence codes for pay statement documents and vouchers.</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Generate pay statements

Pay statements are generated for the pay cycle, pay period, and payment run type that you specify. When you generate pay statements, all released earnings that fit the specified criteria are automatically collected.

Before you generate a pay statement, you must generate and release the earnings for the pay cycle and pay period. For more information, see [Generate earnings](generate-earnings.md) and [Work with existing earnings](work-with-existing-earnings.md).


> [!NOTE]
> <P>If a worker payment occurs outside Microsoft Dynamics AX, see “Record payments made outside Payroll” in <A href="pay-statements-and-the-payment-generation-process.md">Pay statements and the payment generation process</A>.</P>



To generate pay statements, follow these steps:

1.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Generate pay statements**.
    
    You can also generate a single pay statement from the **Payroll** tab in the **Worker** or **Position** forms.

2.  In the **Pay cycle** field, select the pay cycle that includes the earnings to generate the pay statement for.

3.  In the **Pay period** field, select the pay period that includes the earnings. The pay periods that are displayed are available for the selected pay cycle. The default pay period is the first open pay period, but you can select any open pay period from the list.

4.  In the **Payment run type** field, select the payment run type. The default payment run type is **Primary**, which is used for regular payroll runs.
    
    The **Manual** payment run type is used to enter payments, such as vested stock options, that are made outside payroll. If you select **Manual** in the **Payment run type** field, the **Disable accounting** check box is displayed. When this check box is selected, accounting information isn’t recorded or posted to the general ledger. For more information, see [Pay statements and the payment generation process](pay-statements-and-the-payment-generation-process.md).
    

    > [!NOTE]
    > <P>If the earning code for a released earning isn’t set up for the selected payment run type, the earning isn’t included on the pay statement. If the accrual rate basis for a benefit accrual plan is a fixed amount, earning lines that are related to the plan are processed only in primary payroll runs.</P>



5.  Click **OK** to generate pay statements. A message is displayed when the pay statements are generated successfully.

6.  Close the form.

7.  Verify that the batch job finished correctly. (Click **Home** \> **Inquiries** \> **Batch jobs** \> **My batch jobs**. Click **Log**, and then inspect the log for any errors that occurred.)

To post pay statements to the general ledger, see [Post payroll and generate vendor invoices](post-payroll-and-generate-vendor-invoices.md). To submit pay statements for payment, see [Issue worker payments](issue-worker-payments.md).

Back to top

## Delete pay statements

You can delete pay statements only if they haven’t been posted or submitted to Accounts payable for payment, and if the payment hasn’t been issued. If pay statements have been posted, submitted, or paid, you must reverse the pay statement instead of deleting it. For more information, see [Work with existing payroll payments](work-with-existing-payroll-payments.md).

This is what happens when you delete a pay statement:

  - The earnings statement lines aren’t deleted, and you can include them when you generate a new pay statement.

  - Any arrearages that were created by the pay statement are deleted. If an amount in arrears is partially or fully recovered by a later pay statement, you must delete the pay statement that recovered the amount before you delete the pay statement that created the arrearage.

To delete a pay statement, follow these steps:

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Select the pay statement to delete, and then click **Delete**.

Back to top

## Modify earning lines on pay statements

You maintain earning lines in the **Earnings statement** form. You can remove earning lines from a pay statement, but you can’t add or change earning lines. To add or change earning lines, you must first delete the pay statement, as described in the following procedures.

### Add earning lines to a pay statement

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Select the pay statement.

3.  Click **Delete**.

4.  Click **Payroll** \> **Common** \> **Earnings statements** \> **Earnings statements**.

5.  Double-click the earnings statement that contains the lines for the deleted pay statement.

6.  Review the lines that weren’t included on the deleted pay statement, and make any changes or corrections. Most often, missing lines were unintentionally deleted from the pay statement or haven’t been released. The lines might be in a different pay cycle or pay period, or the earning code for the earning line isn’t set up for the selected payment run type.

7.  Generate a new pay statement.

### Remove earning lines from a pay statement

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Double-click the pay statement to remove lines from.

3.  Click **Edit**.

4.  Select the earning lines, and then click **Remove**.
    
    The earning lines that you remove aren’t deleted from Payroll, and you can include them on a future pay statement.

5.  In the message bar, click **Recalculate**.
    

    > [!IMPORTANT]
    > <P>You must recalculate the pay statement before you can submit it for payment or post it to the general ledger.</P>



6.  Close the form.

### Modify earning lines on a pay statement

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Select the pay statement.

3.  Click **Delete**.

4.  Click **Payroll** \> **Common** \> **Earnings statements** \> **Earnings statements**.

5.  Put the earnings for the deleted pay statement on hold, change the earning lines if you have to, and then release the earnings. For instructions, see [Work with existing earnings](work-with-existing-earnings.md).

6.  Generate a new pay statement.

Back to top

## Modify benefit lines and tax lines on pay statements

You can add or remove benefit lines. You can also change benefit lines that were added by a user. And if benefit lines were created automatically, you can change them if the benefit plan isn’t locked for pay statements. For more information, see [Benefit elements (form)](https://technet.microsoft.com/library/hh209498\(v=ax.60\)).

You can add, remove, and change tax lines, except for Medicare and Federal Insurance Contributions Act (FICA) tax lines.

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Double-click the pay statement to modify.

3.  Click **Edit**.

4.  Click the **Benefit calculations** link and make any changes to the benefit lines. Benefit lines that can’t be changed are marked with a red circle that has a line through it. Benefit lines that have already been changed by a user are marked with a pencil icon.
    

    > [!WARNING]
    > <P>If arrearages were created when the pay statement was generated, the arrearage amounts are displayed in the <STRONG>Arrears</STRONG> FactBox. The arrearages might cause the pay statement benefit lines to differ from the lines and amounts that you expect. For more information, see <A href="pay-statements-and-the-payment-generation-process.md">Pay statements and the payment generation process</A>.</P>



5.  Click the **Tax calculations** link and make any changes to the tax lines. Tax lines that can’t be modified are marked with a red circle that has a line through it. Tax lines that have already been changed by a user are marked with a pencil icon.

6.  In the message bar, click **Recalculate**.
    

    > [!IMPORTANT]
    > <P>You must recalculate the pay statement before you can submit it for payment or post it to the general ledger.</P>



Back to top

## Modify benefit accrual lines on pay statements

Benefit accrual lines are created when you submit a pay statement for payment. You can’t add, remove, or change benefit accrual lines. If the benefit accrual lines on a pay statement create incorrect balances in a benefit accrual plan, you must change the plan balances. If you change the worker’s plan balances, the amounts on the pay statement aren’t updated. The change is reflected on the next pay statement that is processed. For more information, see [Benefit accrual plan tasks](benefit-accrual-plan-tasks.md).

Back to top

## Reverse a pay statement

To reverse a pay statement that has been posted or submitted for payment, see [Work with existing payroll payments](work-with-existing-payroll-payments.md).

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
<td><p>To work with pay statements, you must be a member of a security role that includes this duty:</p>
<ul>
<li><p>Maintain pay statements (PayrollPayStatementGenerationMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To work with pay statements, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p>Maintain accounting distributions (AccountingDistributionsDelete)</p></li>
<li><p>Maintain benefit register report (PayrollBenefitRegisterMaintain)</p></li>
<li><p>Maintain Form W-2 box adjustments (PayrollFormW2BoxReportingAdjMaintain)</p></li>
<li><p>Maintain pay statements (PayrollPayStatementMaintain)</p></li>
<li><p>Maintain pay statements (PayrollPayStatementReportMaintain)</p></li>
<li><p>Reverse a pay statement (PayrollPayStatementReversalProcess)</p></li>
<li><p>Generate pay statements (PayrollPayStatementsGenerationProcess)</p></li>
<li><p>Maintain payroll tax history (PayrollTaxHistoryMaintain)</p></li>
<li><p>Maintain tax register report (PayrollTaxRegisterReportMaintain)</p></li>
<li><p>Maintain worker arrears (PayrollWorkerArrearMaintain)</p></li>
<li><p>Maintain worker payment register report (PayrollWorkerPaymentRegister)</p></li>
<li><p>View subledger journal account entry (SubledgerJournalAccountEntryView)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find related tasks

[Generate earnings](generate-earnings.md)

[Work with existing earnings](work-with-existing-earnings.md)

[Issue worker payments](issue-worker-payments.md)

[Work with existing payroll payments](work-with-existing-payroll-payments.md)

  


