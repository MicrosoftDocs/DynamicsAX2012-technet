---
title: Work with existing payroll payments
TOCTitle: Work with existing payroll payments
ms:assetid: 1a79bd00-b070-497d-9aec-f3b5b9862899
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677327(v=AX.60)
ms:contentKeyID: 49384101
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- worker pay
- pay statement
- pay statements
- payroll payment
- payroll payments
- worker payroll
---

# Work with existing payroll payments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to reprint pay statements, replace paychecks that have been lost or damaged, and do similar tasks after pay statements are generated or payments are issued to workers.

## What do you want to do?

Learn more about...

Prerequisites

Print or reprint pay statements for previously processed payments

Reprint a check for a worker before the payment journal is posted

Reissue a check to a worker after the payment journal is posted

Void a check payment and reverse a pay statement

Re-create an ACH file

Technical information for system administrators

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Issue worker payments](issue-worker-payments.md)

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
<td><p>Tasks</p></td>
<td><p>Pay statements have been generated. For more information, see <a href="work-with-pay-statements.md">Work with pay statements</a>.</p></td>
</tr>
</tbody>
</table>


Back to top

## Print or reprint pay statements for previously processed payments

To print or reprint pay statements for payments that were previously processed, follow these steps:

1.  Click **Payroll** \> **Reports** \> **Pay statements**.
    
    You can also print pay statements from the **Pay statements** list page and details form.

2.  In the **Pay cycle** field, select the pay cycle for the pay statements to print.

3.  In the **Pay period** field, select the pay period for the pay statements. The pay periods that are displayed are available for the pay cycle.

4.  Click **OK**.

Back to top

## Reprint a check for a worker before the payment journal is posted

If a check was damaged when it was printed, you can follow these steps to reprint the check for a worker, as long as the payment journal hasn’t been posted:

1.  If you have permissions to change values in the **Cash and bank management parameters** form and you want to use the same check number, complete these tasks. Otherwise, continue to the next step.
    
      - Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.
    
      - In the **Check setup** section, select the **Allow check reuse** check box.

2.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Payment journal**.

3.  Select the payment journal, and then click **Lines** to open the **Journal voucher** form.

4.  Select the check payment to reprint and complete these tasks:
    
    1.  If you did the first step in this procedure, click **Payment status** and select **Reuse** to remove the check number from the bank journal.
    
    2.  If you didn’t do the first step in this procedure, click **Payment status** and select **Rejected**. When you’re prompted, select **Yes** to void the check and remove the check number from the bank journal. Set the **Payment status** field to **None**.

5.  Select **Functions**, and then select **Generate payments** to generate payments that have a **None** status, and that match the method of payment and bank account that you selected.

6.  In the **Generate payments** form, select the bank account and the check method of payment, and then click **OK**.The **Payroll check payment** form opens. Verify the check number in the **From** field and the print destination, and then click **OK** to print the check.

7.  Verify that the check was printed correctly and that the payment status is set to **Sent** in the **Journal voucher** form.

Back to top

## Reissue a check to a worker after the payment journal is posted

Complete these steps when check payments were generated and the payment journal was posted, but you want to reprint a check for a worker. For example, you might have to reprint a check that was lost.

To issue another check for a worker, follow these steps:

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Select the check and then click **Payment reversal** to open the **Payment reversal** form.
    
    You can reverse only checks that have a payment status of **Paid**.

3.  Complete the information in the **Payment reversal** form, and then click **OK**.

4.  Click **Cash and bank management** \> **Journals** \> **Check reversals**. Select the journal that contains the reversal.

5.  From the **Post** menu, select **Post** to unsettle the original payment journal record from the invoice and create an offset transaction that will be settled to the original payment. The invoice will have an outstanding amount that hasn’t been settled.
    

    > [!NOTE]
    > <P>This process occurs automatically if the <STRONG>Use review process for payment reversals</STRONG> check box isn’t selected in the <STRONG>Cash and bank management parameters</STRONG> form.</P>



6.  Click **Payroll** \> **Common** \> **Pay statements** \> **Issued pay statements**.

7.  Select the pay statement, and then click **Submit to reissue**.
    
    A new payment journal is created that has the new line. An invoice isn’t created.

8.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Payment journal**.

9.  Select the payment journal that was just created, and then select **Lines** to open the **Journal voucher** form.

10. Select **Functions**, and then select **Generate payments** to generate payments that have a **None** status, and that match the method of payment and bank account that you selected.

11. In the **Generate payments** form, select the bank account and the check method of payment, and then click **OK**. The **Payroll check payment** form opens. Verify the check number in the **From** field and the print destination, and then click **OK** to print the check.

12. Verify that the payment status is set to **Sent** in the **Journal voucher** form.

Back to top

## Void a check payment and reverse a pay statement

Sometimes you have to void a check. For example, if the payment journal was already posted, you might have to void a check that was printed for a worker who should not have been paid.

If the check or Automated Clearing House (ACH) file that contains the payment hasn’t been created, but the pay statement has been submitted or posted, you don’t have to void the payment, but you do have to reverse the pay statement. Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**. Then start this procedure at step 7.

If the pay statement hasn’t been submitted or posted, delete the pay statement instead of reversing it. For more information, see [Work with pay statements](work-with-pay-statements.md).

To void a check and reverse the payment, follow these steps:

1.  Click **Cash and bank management** \> **Common** \> **Checks**.

2.  Select the check, and then click **Payment reversal** to open the **Payment reversal** form.
    
    You can reverse only checks that have a payment status of **Paid**.

3.  Complete the information in the **Payment reversal** form, and then click **OK**.

4.  Click **Cash and bank management** \> **Journals** \> **Check reversals**. Select the journal that contains the reversal.

5.  From the **Post** menu, select **Post** to unsettle the original payment journal record from the invoice and create an offset transaction that will be settled to the original payment. The invoice will have an outstanding amount that hasn’t been settled.
    

    > [!NOTE]
    > <P>This process occurs automatically if the <STRONG>Use review process for payment reversals</STRONG> check box isn’t selected in the <STRONG>Cash and bank management parameters</STRONG> form.</P>



6.  Click **Payroll** \> **Common** \> **Pay statements** \> **Issued pay statements**.

7.  Select the pay statement, and then click **Reverse**.
    

    > [!IMPORTANT]
    > <P>Arrearage amounts aren’t reversed when you reverse a pay statement. If arrearages were created or recovered on the pay statement that you reverse, you must manually adjust the worker’s arrearage balance in the <STRONG>Worker arrears</STRONG> form. If an arrearage was created, the amount of the arrearage is in the <STRONG>Arrears</STRONG> FactBox. To determine whether an arrearage was recovered, use the <STRONG>Worker arrears</STRONG> form.</P>



8.  Click **Yes** when you are prompted to continue. A new pay statement that has amounts that are the opposite of the amounts on the original pay statement is created, and a message displays the ID of the reversing pay statement.
    
    A message bar appears on the original pay statement and indicates that the pay statement was reversed. A message bar also appears on the new pay statement to indicate that it was created to reverse a pay statement. In addition, the new pay statement displays the original pay statement ID and provides an option to open the reversed pay statement.

9.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

10. If the original pay statement was submitted, select the new reversed pay statement that was created, and then click **Submit for payment**.
    

    > [!NOTE]
    > <P>If the original pay statement was posted but not submitted, go to step 13.</P>



11. Optional: Select the **Post the selected pay statement** check box.
    
    Skip this step if the original pay statement wasn’t posted.

12. Click **Submit**. A new invoice with opposite values is created, posted, and settled with the original invoice.
    
    A payment journal isn’t created.

13. If the original pay statement was posted but not submitted, select the new reversed pay statement that was created. On the **Action Pane**, on the **Financials** tab, click **Post**.

14. Don’t select the **Submit for payment after posting** check box. Click **Post**.

Back to top

## Re-create an ACH file

To re-create an ACH file for a group of electronic payments when the payment journal hasn’t been posted, follow these steps:

1.  Click **Payroll** \> **Periodic** \> **Pay statement processing** \> **Payment journal**.

2.  Select the payment journal that contains the lines to re-create the file for, and then click **Lines** to open the **Journal voucher** form.

3.  Select the lines to re-create the file for.

4.  Select **Payment status**, and then click **None**.

5.  Select **Functions**, and then select **Generate payments** to generate payments that have a **None** status, and that match the method of payment and bank account that you selected.

6.  In the **Generate payments** form, select the bank account and the check method of payment, and then click **OK**.

7.  In the **Payroll electronic** (Direct deposit) form, enter the path (which includes the file name), enter an effective date, and optionally select the **Pay statement** check box to print the pay statements. Click **OK** to create the ACH file. A message displays the number of transactions and prenotes that were created.

8.  Verify that the payment status is set to **Sent** in the **Journal voucher** form.

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
<td><p>To work with existing payroll payments, you must be a member of a security role that includes this duty:</p>
<ul>
<li><p>Issue payments to workers (PayrollIssueWorkerPaymentsMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To work with existing payroll payments, you must be a member of a security role that includes these privileges:</p>
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

[Journal voucher - Payroll payment journal (form)](https://technet.microsoft.com/en-us/library/jj677395\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

