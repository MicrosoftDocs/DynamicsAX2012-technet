---
title: Issue worker payments
TOCTitle: Issue worker payments
ms:assetid: 068274eb-0019-4374-8ec9-f644d77c64d0
ms:mtpsurl: https://technet.microsoft.com/library/JJ677320(v=AX.60)
ms:contentKeyID: 49384092
author: tonyafehr
ms.date: 11/15/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- electronic payments
- electronic payment
- worker pay
- worker payments
- Classes.BankPositivePayExport
- electronic payroll
- pay check
- paycheck
- worker payment
- pay checks
- paychecks
audience: Application User
ms.search.region: USA
---

# Issue worker payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to submit pay statements, generate checks or electronic payments, generate a positive pay file for payroll, and post the payment journal.

You can pay workers by check or by electronic payment. When you submit pay statements, an invoice is created and posted to the general ledger for the sum of the worker’s net pay for the payroll vendor that is set up in the **Payroll parameters** form. A payment journal that has lines is created, which lets you generate and post payments. In addition, you can optionally post the payroll costs that are associated with workers to the general journal when you submit payments.

## What do you want to do?

Learn more about...

This task is part of a bigger process

Prerequisites

Submit pay statements for multiple workers in a pay period

Submit individual pay statements

Generate checks or electronic payments for a payment journal

Generate a positive pay file for payroll

Post a payment journal

Technical information for system administrators

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Processing payroll](processing-payroll.md)

[Work with existing payroll payments](work-with-existing-payroll-payments.md)

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
<td><p>AX 2012 R2 or Microsoft Dynamics AX 2012 R3 Cumulative Update 8</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
<tr class="odd">
<td><p>Related configuration tasks</p></td>
<td><p>You must complete these tasks before you can post payroll and generate vendor invoices:</p>
<ul>
<li><p>Set the <strong>Payroll clearing account</strong> field on the <strong>Calculation settings</strong> tab in the <strong>Payroll parameters</strong> form. For more information, see <a href="https://technet.microsoft.com/library/jj677433(v=ax.60)">Payroll parameters (form)</a>.</p></li>
<li><p>Set the <strong>Check method of payment</strong>, <strong>Vendor account for worker payments</strong>, <strong>Payment journal name</strong>, and <strong>Procurement category</strong> fields on the <strong>Payment issuance</strong> tab in the <strong>Payroll parameters</strong> form. For more information, see <a href="https://technet.microsoft.com/library/jj677433(v=ax.60)">Payroll parameters (form)</a>.</p></li>
<li><p>Before you can generate a positive pay file for payroll, you must first set up positive pay. For more information, see <a href="set-up-positive-pay.md">Set up positive pay</a>.</p></li>
<li><p>If you generate electronic payments, make sure that the <strong>Electronic method of payment</strong> field is set on the on the <strong>Payment issuance</strong> tab in the <strong>Payroll parameters</strong> form, and that you’ve entered the bank account disbursements for each worker. For more information about worker bank account disbursements, see <a href="https://technet.microsoft.com/library/jj677398(v=ax.60)">Bank account disbursements (form)</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Submit pay statements for multiple workers in a pay period

Complete these steps to create a payment journal for multiple pay statements at the same time.

You must generate and release earnings before you generate pay statements. For more information, see [Generate earnings](generate-earnings.md).

To submit pay statements for multiple workers at the same time, following these steps:

1.  Generate pay statements so that earnings, benefits, and taxes are calculated. For more information, see [Work with pay statements](work-with-pay-statements.md).
    

    > [!TIP]
    > <P>Before you generate pay statements, we recommend that you view the <STRONG>Pay statements to recalculate</STRONG> list page to verify that no pay statements must be recalculated. For more information, see “Modify pay statements” in <A href="work-with-pay-statements.md">Work with pay statements</A>.</P>



2.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Submit pay statements**.

3.  In the **Pay cycle** field, select the same pay cycle that you selected when you generated and released earnings.

4.  In the **Pay period** field, select the same pay period that you selected when you generated and released earnings. The pay periods that are displayed are available for the pay cycle. The default pay period is the first open pay period, but you can select any open pay period from the list.

5.  Click **OK** to submit the pay statements. A vendor invoice for the sum of the net pay for all pay statements is created and posted. A payment journal that has lines is also created and posted, so you can generate and post payments. A message is displayed to indicate that the payment journal was generated successfully and that a voucher and invoice details were created.

6.  Close the confirmation message.

7.  Click **Payroll** \> **Common** \> **Pay statements** \> **Submitted pay statements**. A list of submitted statements is displayed and an icon appears in the first column of the **Pay statement** grid to indicate that the payment was submitted.

8.  View the payment journal, and then generate checks and electronic payments. Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Payment journal**.

Back to top

## Submit individual pay statements

To create a payment journal for an individual pay statement, follow these steps:

1.  Generate pay statements so that earnings, benefits, and taxes are calculated. For more information, see [Work with pay statements](work-with-pay-statements.md).

2.  Click **Payroll** \> **Common** \> **Pay statements** \> **Calculated pay statements**.

3.  Select the worker pay statement to create the payment journal for, and then click **Submit for payment**.
    
    The **Submit for payment** button is also available in the **Pay statement** form.

4.  Optional: Select the **Post the selected pay statement** check box to post the pay statement.
    
    You can post the pay statements as a separate step at any time. Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Post pay statements**.

5.  Click **Submit** to submit the pay statements. A vendor invoice is created and posted for the net pay of the pay statement. A payment journal that has lines is also created, so you can generate and post the payment. A message is displayed to indicate that the payment journal was generated successfully and that a voucher and invoice details were created.

6.  Close the message. An icon appears in the first column of the **Pay statement** grid to indicate that the payment was submitted.

7.  View the payment journal and generate checks and electronic payments. Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Payment journal**.

8.  Continue with “Generate checks or electronic payments for a payment journal” in this topic.

Back to top

## Generate checks or electronic payments for a payment journal

To generate checks and electronic payments for workers, follow these steps after you submit the pay statements and generate the payment journal.


> [!WARNING]
> <P>If you didn’t finish the bank account disbursements before the pay statements were generated, the worker will be paid by check. For more information, see <A href="https://technet.microsoft.com/library/jj677398(v=ax.60)">Bank account disbursements (form)</A>.</P>



1.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Payment journal**.

2.  Select the payment journal, and then click **Lines** on the action strip to view the **Journal voucher**.

3.  Validate that the number of vouchers is correct. There is one journal voucher line for each check pay statement and one or more journal voucher lines for each electronic pay statement.

4.  From the **Functions** menu, select **Generate payments**.
    

    > [!NOTE]
    > <P>You must complete this step separately for electronic and check payments. Therefore, if you’re generating both, you must complete this step two times.</P>



5.  In the **Generate payments** form, select the method of payment and the bank account.

6.  Click **OK** to generate the payment for the records that match the method of payment and the bank account.
    
      - If you selected **Check method of payment**, the **Payroll check payment** form opens. Verify the starting check number in the **From** field and the printing destination, and then click **OK** to print the checks.
    
      - If you selected the electronic method of payment, the **Payroll electronic** (Direct deposit) form opens. Enter the path where you want the ACH file to be created (including the file name), enter an effective date and the printing destination, and optionally, select the **Pay statement** check box to print the pay statements. Click **OK** to create the ACH file.
        

        > [!TIP]
        > <P>You can later print pay statements from the <STRONG>Reports</STRONG> menu.</P>

        
        The payment status is set to **Sent** for each payment that was generated.

Back to top

## Generate a positive pay file for payroll

You can generate an electronic list of payroll checks that is provided to the bank. When a payroll check is presented to the bank, the bank compares the check to the list of checks. If the check matches what the bank has on file in the list, the bank clears the check. If there is a difference, the bank holds the check for review.

To generate a positive pay file for payroll, follow these steps:

1.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Payroll positive pay**.

2.  In the **Cut-off date** field, enter the last check date to include in the positive pay file. All checks that haven’t been included in a positive pay file through this check date are included in the file.

3.  Click **OK**.
    
    If you receive this error message, contact a system administrator because security for the positive pay file folder isn’t set up correctly and you can’t complete this procedure: **Endpoint is not allowed to perform this action.**

## Confirm a positive pay file for payroll

After the checks that are listed in a payroll positive pay file are paid, you receive a confirmation number from the bank. Then, you can confirm the positive pay file in Microsoft Dynamics AX. When you confirm a positive pay file, you record the confirmation number that you received from the bank.

To confirm a positive pay file, follow these steps:

1.  Click **Payroll** \> **Inquiries** \> **Payroll positive pay file summary**.

2.  Select a payroll positive pay file that has a status of **Created**.

3.  Click **Confirmation**.

4.  Enter the confirmation number that you received from the bank.

5.  Click **OK**.

## If required: Recall a positive pay file

If you have to change a payroll positive pay file, you can recall it. When you recall a positive pay file, the field that indicates whether each check has been included in a positive pay file is reset. Then, you can create a new positive pay file.

To recall a positive pay file, follow these steps:

1.  Click **Payroll** \> **Inquiries** \> **Payroll positive pay file summary**.

2.  Select a payroll positive pay file that has a status of **Created**.

3.  Click **Recall**. A message confirms that the recall process was successful.

Back to top

## Post a payment journal

You can post a payment journal after you generate checks and electronic payments, as described earlier in this topic.

To post a payment journal, follow these steps:

1.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Payment journal**.

2.  Select the payment journal, and then click **Lines** on the action strip to view the **Journal voucher** form.

3.  From the **Post** menu, select **Post**. The payment journal lines are settled to the vendor invoice that was created and posted. A message is displayed to indicate the number of vouchers that were posted.

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
<td><p>To issue payments to workers, you must be a member of a security role that includes this duty:</p>
<ul>
<li><p>Issue payments to workers (PayrollIssueWorkerPaymentsMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To issue payments to workers, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p>View worker bank accounts (HcmWorkerBankAccountView)</p></li>
<li><p>Maintain payment journal transactions (LedgerJournalPayrollDisbursementMaintain)</p></li>
<li><p>Generate posted transactions by journal report (LedgerTransPerJournalGenerate)</p></li>
<li><p>Mark the payment as confirmed for the payroll disbursement journal (PaymReconConfPayrollDisbursementProcess)</p></li>
<li><p>Set status of the payment to none for the payroll disbursement journal (PaymReconNonePayrollDisbursementProcess)</p></li>
<li><p>Mark the payment as voided for the payroll disbursement journal (PaymReconRejPayrollDisbursementProcess)</p></li>
<li><p>Mark the payment as sent for the payroll disbursement journal (PaymReconSentPayrollDisbursementProcess)</p></li>
<li><p>Submit pay statements (PayrollSubmitPayStatement)</p></li>
<li><p>Process vendor settlements (VendOpenTransProcess)</p></li>
<li><p>Generate vendor payment journal report (VendPaymentJournal_NAGenerate)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find form help

[Journal voucher - Payroll payment journal (form)](https://technet.microsoft.com/library/jj677395\(v=ax.60\))

  


