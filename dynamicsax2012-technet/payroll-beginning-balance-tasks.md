---
title: Payroll beginning balance tasks
TOCTitle: Payroll beginning balance tasks
ms:assetid: 858d1dbf-9e4e-4787-9036-c9e1c6a8c289
ms:mtpsurl: https://technet.microsoft.com/library/Dn754852(v=AX.60)
ms:contentKeyID: 62504013
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- beginning balances
audience: Application User
ms.search.region: USA
---

# Payroll beginning balance tasks 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

If you change from a different payroll system to Microsoft Dynamics AX in the middle of the calendar year, you must enter beginning balances for earnings, deductions, contributions, benefits, and taxes so that you can complete W-2s and other year-end tasks.

This illustration shows what you have to do to enter payroll beginning balances. The numbers correspond to the procedures later in this topic.

![Enter payroll beginning balances process](images/Dn754852.PayrollBegBalances(AX.60).gif "Enter payroll beginning balances process")

## This task is part of a bigger process

This illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time.

For an overview of the process, see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

![Basic steps for setting up Payroll the first time](images/JJ677367.Payroll_Set_up_payroll_basic(AX.60).gif "Basic steps for setting up Payroll the first time")

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

For more information on the planning prerequisites, see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

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
<td><p>Microsoft Dynamics AX 2012 R2</p>
<p>Work cycles and work periods require Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
<tr class="odd">
<td><p>Planning</p></td>
<td><p>Decide on which date the payroll beginning balances should start.</p></td>
</tr>
<tr class="even">
<td><p>Planning</p></td>
<td><p>Gather the following information from the previous payroll system:</p>
<ul>
<li><p>Earnings</p></li>
<li><p>Benefits</p></li>
<li><p>Deductions</p></li>
<li><p>Employee taxes</p></li>
<li><p>Employer taxes</p></li>
<li><p>Year-to-date (YTD) amounts</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Planning</p></td>
<td><p>Decide whether to bring over pay statement data in YTD or quarterly increments.</p>
<p>If you enter quarterly beginning balances, you must manually generate and finalize one pay statement for each worker for each closed quarter in the current year. If you enter YTD beginning balances, you must manually generate and finalize only one pay statement per worker.</p></td>
</tr>
</tbody>
</table>


## 1\. Generate earnings statements and pay statements that have beginning balances

Before you can generate pay statements that have beginning balances, you must manually create an earnings statement for each worker. This earnings statement must have earning lines that match the earning amounts in the previous payroll system as of the worker’s last pay period.

To generate an earnings statement and a pay statement that have beginning balances for a worker, follow these steps:

1.  Click **Payroll** \> **Common** \> **Earnings statements** \> **Earnings statements**.

2.  On the **Action Pane**, click **Earnings statement**.

3.  Select the worker to create an earnings statement for.

4.  Select the pay cycle that corresponds with the last pay period for the selected worker.

5.  Select the dates that represent the starting and ending dates of the last pay period.

6.  Add a line to the statement for each earning code that was represented in the previous system.
    
    **Example**
    
    A worker named William Flemming has earned 30,750 in regular pay so far this year, 4,250 in bonus pay, and 1,299 in commission. He is paid semimonthly. When you create an earnings statement for William Flemming, you add these lines.
    
    <table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Lines
  </p> </th>
    <th> <p>
   
	 Fields
  </p> </th>
    <th> <p>
   
	 Values
  </p> </th>
  </tr>
  <tr>
    <td rowspan="4"> <p>
   
	 Line 1
  </p> </td>
    <td> <p> <strong>Earning code</strong> </p> </td>
    <td> <p>
   
	 RegularPay
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Quantity</strong> </p> </td>
    <td> <p>
   
	 1025
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Unit type</strong> </p> </td>
    <td> <p>
   
	 Hourly
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Rate</strong> </p> </td>
    <td> <p>
   
	 30.00
  </p> </td>
  </tr>
  <tr>
    <td rowspan="4"> <p>
   
	 Line 2
  </p> </td>
    <td> <p> <strong>Earning code</strong> </p> </td>
    <td> <p>
   
	 Bonus
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Quantity</strong> </p> </td>
    <td> <p>
   
	 1.0000
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Unit type</strong> </p> </td>
    <td> <p>
   
	 Each
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Rate</strong> </p> </td>
    <td> <p>
   
	 4,250.00
  </p> </td>
  </tr>
  <tr>
    <td rowspan="4"> <p>
   
	 Line 3
  </p> </td>
    <td> <p> <strong>Earning code</strong> </p> </td>
    <td> <p>
   
	 Commission
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Quantity</strong> </p> </td>
    <td> <p>
   
	 1.0000
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Unit type</strong> </p> </td>
    <td> <p>
   
	 Each
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Rate</strong> </p> </td>
    <td> <p>
   
	 1,299.00
  </p> </td>
  </tr>
</table>


7.  In the **Line details** area, select the **Manual** check box for each earning code line that you added for the worker.
    

    > [!IMPORTANT]
    > <P>This step is important. Be sure to select the <STRONG>Manual</STRONG> check box for <EM>each</EM> earnings statement line.</P>



8.  On the **Action Pane**, click **Release earnings statement**.

9.  On the **Action Pane**, click **Pay statement**.

10. In the **Generate pay statements** form, complete these fields, and then click **OK**.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Payment date</strong></p></td>
    <td><p>Enter the last day of worker’s last pay period.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payment run type</strong></p></td>
    <td><p>Select <strong>Manual</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Disable accounting</strong></p></td>
    <td><p>Select this check box.</p>
    <div class="alert">

    > [!IMPORTANT]
    > <P>Your payroll transactions were likely recorded in the general ledger of the previous payroll system. To prevent recording these transactions again in Microsoft Dynamics AX, you must select the <STRONG>Disable accounting</STRONG> check box for each pay statement.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


11. Repeat these steps for each worker.

## 2\. Update pay statements that have beginning balances for benefits and taxes

After you generate pay statements that have beginning balances, you must verify that the pay statements in Microsoft Dynamics AX reflect accurate payroll data. You must also manually update the benefit and taxes information to match the values in the previous payroll system. After you verify that the amounts from the previous payroll system match the amounts on the Microsoft Dynamics AX pay statements, you must finalize the pay statements in Microsoft Dynamics AX.

To review, update, and then finalize a pay statement, follow these steps:

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Select a pay statement to finalize.

3.  On the **Action Pane**, click **Edit**.

4.  Review the earning lines on the pay statement to make sure that the lines match the worker’s information in the previous payroll system.

5.  Click the **Benefit calculations** link.

6.  On the **Benefit deductions** FastTab, add a line and enter a deduction amount for each benefit deduction. The amounts should match the worker’s deduction amounts in the previous payroll system.

7.  On the **Benefit contributions** FastTab, add a line and enter a contribution amount for each benefit contribution. The amounts should match the worker’s contribution amounts in the previous payroll system.

8.  Click the **Tax calculations** link.

9.  On the **Tax deductions** FastTab, add a line and enter a deduction amount for each tax deduction. The amounts should match the worker’s deduction amounts in the previous payroll system.

10. On the **Tax contributions** FastTab, add a line and enter a contribution amount for each tax contribution. The amounts should match the worker’s contribution amounts in the previous payroll system.

11. On the message bar, click **Finalize**.

## 3\. If required: Reverse pay statements

If you finalized a pay statement in Microsoft Dynamics AX and you later notice that the pay statement does not match the payroll amounts in the previous system, you can reverse the pay statement. You then have to generate a new pay statement for the worker.

To reverse a pay statement, follow these steps:

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Select the pay statement to reverse.

3.  On the **Action Pane**, click **Edit**.

4.  On the **Action Pane**, click **Reverse**.

After you reverse the pay statement, you can generate a new pay statement for the worker from the earnings statement that you created previously in the “Generate earnings statements and pay statements that have beginning balances” procedure earlier in this topic. Be sure to fix any incorrect lines on the earnings statement before you generate the new pay statement, and then repeat the “Update pay statements that have beginning balances for benefits and taxes” procedure in this topic.

## Next step

After you have completed the basic setup of the Payroll module, advanced setup tasks might be required. For more information, see [Setting up payroll: Advanced topics](setting-up-payroll-advanced-topics.md).

## Related tasks

[Generate earnings](generate-earnings.md)

[Issue worker payments](issue-worker-payments.md)

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
<td><p>To enter payroll beginning balances, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Maintain earning entry</strong> (PayrollEarningStatementGenerationMaint)</p></li>
<li><p><strong>Issue payments to workers</strong> (PayrollIssueWorkerPaymentsMaintain)</p></li>
<li><p><strong>Post pay statements</strong> (PayrollJournalizePayStatementMaintain)</p></li>
<li><p><strong>Maintain pay statements</strong> (PayrollPayStatementGenerationMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To enter payroll beginning balances, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Generate earnings</strong> (PayrollEarningGenerationProcess)</p></li>
<li><p><strong>Maintain payroll earnings</strong> (PayrollEarningMaintain)</p></li>
<li><p><strong>Earnings import service operation</strong> (PayrollEarningsImportServiceCreate)</p></li>
<li><p><strong>View worker bank accounts</strong> (HcmWorkerBankAccountView)</p></li>
<li><p><strong>Maintain payment journal transactions</strong> (LedgerJournalPayrollDisbursementMaintain)</p></li>
<li><p><strong>Generate posted transactions by journal report</strong> (LedgerTransPerJournalGenerate)</p></li>
<li><p><strong>Mark the payment as confirmed for the payroll disbursement journal</strong> (PaymReconConfPayrollDisbursementProcess)</p></li>
<li><p><strong>Set status of the payment to none for the payroll disbursement journal</strong> (PaymReconNonePayrollDisbursementProcess)</p></li>
<li><p><strong>Mark the payment as voided for the payroll disbursement journal</strong> (PaymReconRejPayrollDisbursementProcess)</p></li>
<li><p><strong>Mark the payment as sent for the payroll disbursement journal</strong> (PaymReconSentPayrollDisbursementProcess)</p></li>
<li><p><strong>Submit pay statements</strong> (PayrollSubmitPayStatement)</p></li>
<li><p><strong>Process vendor settlements</strong> (VendOpenTransProcess)</p></li>
<li><p><strong>Generate vendor payment journal report</strong> (VendPaymentJournal_NAGenerate)</p></li>
<li><p><strong>View budget check errors or warnings inquiry</strong> (BudgetCheckResultsView)</p></li>
<li><p><strong>Create vendor invoices for payroll</strong> (PayrollGenerateVendorInvoice)</p></li>
<li><p><strong>Process payroll posting</strong> (PayrollJournalizePayStatement)</p></li>
<li><p><strong>Maintain accounting distributions</strong> (AccountingDistributionsDelete)</p></li>
<li><p><strong>Maintain benefit register report</strong> (PayrollBenefitRegisterMaintain)</p></li>
<li><p><strong>Maintain Form W-2 box adjustments</strong> (PayrollFormW2BoxReportingAdjMaintain)</p></li>
<li><p><strong>Maintain pay statements</strong> (PayrollPayStatementMaintain)</p></li>
<li><p><strong>Maintain pay statements</strong> (PayrollPayStatementReportMaintain)</p></li>
<li><p><strong>Reverse a pay statement</strong> (PayrollPayStatementReversalProcess)</p></li>
<li><p><strong>Generate pay statements</strong> (PayrollPayStatementsGenerationProcess)</p></li>
<li><p><strong>Maintain payroll tax history</strong> (PayrollTaxHistoryMaintain)</p></li>
<li><p><strong>Maintain tax register report</strong> (PayrollTaxRegisterReportMaintain)</p></li>
<li><p><strong>Maintain worker arrears</strong> (PayrollWorkerArrearMaintain)</p></li>
<li><p><strong>Maintain worker payment register report</strong> (PayrollWorkerPaymentRegister)</p></li>
<li><p><strong>View subledger journal account entry</strong> (SubledgerJournalAccountEntryView)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


