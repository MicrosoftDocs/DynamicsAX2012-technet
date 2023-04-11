---
title: (RUS) Create and post an incentive resolution
TOCTitle: (RUS) Create and post an incentive resolution
ms:assetid: 98112b7e-35b7-4368-975d-7029706303d2
ms:mtpsurl: https://technet.microsoft.com/library/Dn452009(v=AX.60)
ms:contentKeyID: 56713179
author: tonyafehr
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- bonus
- resolution
- incentive
- Forms.RHRMOrderTable
- Forms.RHRMOrderTrans
- Forms.RHRMWorkerListPage
- Forms.RPayEmplCalculate
- Forms.RPayJournalTable
- Forms.RPaySumEmpl
- MsDynAx060.Forms.RHRMOrderTable
- MsDynAx060.Forms.RHRMOrderTrans
- MsDynAx060.Forms.RPaySumEmpl
- MsDynAx060.Forms.RHRMWorkerListPage
- MsDynAx060.Forms.RPayEmplCalculate
- MsDynAx060.Forms.RPayJournalTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post an incentive resolution 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how you can generate Human Resources resolutions that relate to incentive pay. You can create incentive lines to specify to whom you can pay incentive bonuses, and how much you can pay. You can also create incentive lines to create a payroll journal, recalculate payroll taxes for an employee, reverse a posted payroll journal, and restore the original resolution. You can process and view storno adjustments to the journal in the current period by creating a new journal and posting it.

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
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p>Setup tasks</p></td>
<td><p>To create incentive resolutions for employees, the following setup tasks are required:</p>
<ul>
<li><p>Make sure that the staff administration information that is related to rates and salaries are set up in the <strong>Staff administration parameters</strong> form, and that bonus codes, pay types, and bonus types are set up in the <strong>Bonus types</strong> form. For more information, see <a href="rus-set-up-calculation-procedures-for-the-payroll-process.md">(RUS) Set up calculation procedures for the payroll process</a>.</p></li>
<li><p>Make sure that the counters are set up in the <strong>Counter setup</strong> form. For more information, see <a href="rus-set-up-calculation-procedures-for-the-payroll-process.md">(RUS) Set up calculation procedures for the payroll process</a>.</p></li>
<li><p>Make sure that the rates and rate values for incentives are set up in the <strong>Rates</strong> and <strong>Set up rate values</strong> forms. For more information, see <a href="rus-set-up-calculation-procedures-for-the-payroll-process.md">(RUS) Set up calculation procedures for the payroll process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Create an incentive resolution

You can use the **Incentive resolutions** form to create an employee incentive resolution. You can grant an incentive or bonus to an employee after you create and post an incentive resolution. The Payroll department can use information from the incentive resolution that is created by the Human Resources department to create payroll transactions.

To create an incentive resolution, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Bonuses**.

2.  In the **Incentive resolutions** form, click **New** to create an incentive resolution.
    
    Use the information in the following table to create incentive resolutions.
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>Select the name for the bonus journal.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Resolution date</strong></p></td>
    <td><p>Select the incentive resolution creation date.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Bonus code</strong></p></td>
    <td><p>Select the bonus code for the incentive resolution.</p>
    <p>Each bonus code represents a type of bonus, such as a holiday bonus, retention bonus, or health fund bonus.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reason</strong></p></td>
    <td><p>On the <strong>Reason</strong> tab, enter the reason for the incentive resolution.</p></td>
    </tr>
    </tbody>
    </table>


3.  Click **Lines**.

4.  To create an incentive resolution line, in the **Incentive resolution lines** form, click **New**.

5.  In the **Employee** field, select the employee code. All of the relevant details are displayed for the selected employee code.

6.  In the **Bonus** field, enter the incentive amount that indicates how much you can pay for incentive bonuses.
    

    > [!NOTE]
    > <P>If you create an incentive resolution in the Human Resources department, the information can be used by the Payroll department to create payroll transactions during the payroll journal creation based on the list of employees and values from the employee resolution.</P>



7.  To validate the bonus, click **Validate**, and then click **OK** in the **Check journal** form.

8.  To post the incentive resolution lines, click **Post**, and then click **OK** in the **Post journal** form.
    

    > [!NOTE]
    > <P>The Human Resources department should collect employee signatures to confirm that the employees are informed about the incentive resolution.</P>



9.  Optional: Click **Restore** to cancel the posting. If you do this, you can post this incentive resolution, and related payments are made to the employee later.

10. To print the employee’s incentive resolution, click **Print** \> **Form T-11**.

You can verify the following details of the employee’s incentive resolution in the **Worker** form:

  - Click **Payroll (Russia)** \> **Common** \> **Employees**. Double-click the employee record for which the resolution is created.

  - To verify the employee’s payroll transactions for the selected calculation period in the **Payments and deductions registration** form, in the **Worker** form, on the **Payroll** tab, click **Payments and deductions**.

  - To view all of the employee incentive resolution details for the specified calculation period, including incentive resolution pay, click **History** to open the **History** form.

## 2\. Create a payroll journal for an incentive resolution

You can use the **Payroll journal** form to create a payroll journal for an incentive resolution.

To create a payroll journal, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Payroll journal** \> **Payroll journal**.

2.  Click **New** to create a payroll journal.

3.  On the **General** tab, in the **Number of incentive resolution** field, select the reference number of the incentive resolution that is created in the Staff administration module.

4.  Click **From order** to retrieve the incentive details from the employee resolution that you created in the Staff administration module.

5.  To view the created payroll journal lines, click **Lines**.

6.  To validate the journal, click **Validate**, and then click **OK** in the **Check journal** form.

7.  To post the journal, click **Post**, and then click **OK** in the **Post journal** form.

8.  On the **Employees** list page, select the specific employee that the incentive pay is created for.

9.  To verify the employee’s payroll transactions for the selected calculation period, in the **Payments and deductions registration** form, on the **Payroll** tab, click **Payments and deductions**.

To cancel the posting of the journal, click **Reverse** in the **Payroll journal** form. To view the storno adjustment for the selected journal line, click **View the storno** in the **Payroll journal** form.

## 3\. Recalculate the payroll taxes for the employees

After the incentive procedures are calculated, you can run recalculations to include any new updates. The pay types that are used to register these incentive payments are linked to the calculation routine that is related to the personal taxation of employees. For example, if you change the size of the taxable earnings, the accountant must recalculate the employee’s personal taxes. You can use the **Recent transactions** form to view the list of employees that you made changes for. You can recalculate the salaries for these employees without running a new payroll calculation for all company employees. To close the payroll calculation, you must first close the recalculation of personal income taxes.

To recalculate the payroll taxes, follow these steps:

1.  Click **Payroll (Russia)** \> **Payroll calculation** \> **Recent transactions**.

2.  Click **New** to create a transaction.

3.  In the **Employee** field, select the employee code.

4.  In the **Procedure code** field, select the calculation procedure code for incentives.

5.  To recalculate personal income tax for only the selected employee, click **Recalculate current**. To recalculate personal income tax for all employees, click **Recalculate all**.

## 4\. Reverse a posted payroll journal line and restore the original resolution

You can use the **Payroll journal** form to reverse the posted payroll journal in the open calculation period. If the cancellation is made in the same period in which the journal was posted, the journal status is not posted. The journal lines that are created by posting payroll transactions are deleted, and the journal is ready for editing and further posting. If the cancellation is made in the period following the one in which the journal was posted, the new journal is created with storno lines and posted.

To reverse a posted payroll journal in the same payroll period, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Payroll journal** \> **Payroll journal**.

2.  Select the posted payroll journal.

3.  Click **Reverse**, and then click **OK** in the **Restore journal** form.
    
    The **Posted** check box is automatically cleared, which indicates that the journal status is not posted. This is because you canceled the incentive resolution in the same payroll period in which the journal was posted. The payroll transactions that are created by journal posting are deleted, and the journal is ready for further modification and posting.

4.  To delete the selected payroll journal transaction lines for this reversed incentive resolution, click **Lines**.

5.  In the **Payroll journal** form, on the **General** tab, in the **Number of incentive resolution** field, the reference number of the incentive resolution that is created in the Staff administration module is deleted.

6.  To delete the specific journal line in the **Payroll journal** form and the selected payroll journal lines in the **Payroll journal lines** form, click **Delete**.
    

    > [!NOTE]
    > <P>In the <STRONG>Payments and deductions registration</STRONG> form, all of the incentive resolution lines that are deleted for the same payroll periods are deleted.</P>



To reverse a posted payroll journal in a future period, follow these steps:

1.  Create and post a payroll journal for an incentive resolution. For more information, see 2. Create a payroll journal for an incentive resolution.

2.  Use the information in the table to make sure that all the listed payroll calculation tasks are completed for the previous periods.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Category</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Related tasks</p></td>
    <td><p></p>
    <ul>
    <li><p>Calculate all necessary procedures</p></li>
    <li><p>Recalculate recent transaction changes.</p></li>
    <li><p>Calculate off- budget funds and income tax</p></li>
    <li><p>Generate the salary journal.</p></li>
    <li><p>Close the payroll period.</p></li>
    </ul>
    <p>For more information about creating average earnings, calculating salaries, and calculating funds, see the <a href="rus-generate-pay-statements.md">(RUS) Generate pay statements</a> topic.</p></td>
    </tr>
    </tbody>
    </table>


3.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Payroll journal** \> **Payroll journal**.

4.  Click **Reverse**, and then click **OK** in the **Restore journal** form. A journal with the same incentive resolution reference number and line number is created and posted.

5.  Click **Lines** to view the payroll transactions for the period and the incentive amount with a negative sign.

## Next step

[(RUS) Set up vacations, business trips, and incentives for the payroll process](rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md)

(RUS) Register vacations, business trips, and calculate compensation

## Related tasks

[(RUS) Support the workforce management process](rus-support-the-workforce-management-process.md)

[(RUS) Generate pay statements](rus-generate-pay-statements.md)

[(RUS) Payroll accounting reports](rus-payroll-accounting-reports.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>CIS Payroll</strong> and <strong>CIS Staff administration</strong> configuration keys.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p>Compensation and benefits manager</p></li>
<li><p>Payroll assistant</p></li>
</ul>
<p>To configure benefits, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To configure benefits, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privileges</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enable workforce management process</strong></p></td>
<td><p>HcmEmploymentTermMaintain</p></td>
<td><p>Create an incentive resolution.</p></td>
</tr>
<tr class="even">
<td><p><strong>Inquire into workforce management process</strong></p></td>
<td><p>HcmEmploymentTermView</p></td>
<td><p>Recalculate the payroll taxes for the employees.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


