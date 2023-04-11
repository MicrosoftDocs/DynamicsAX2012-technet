---
title: (RUS) Issue payments to workers
TOCTitle: (RUS) Issue payments to workers
ms:assetid: e617e3cf-f503-4529-95d3-5ee9a6cd3d49
ms:mtpsurl: https://technet.microsoft.com/library/Dn762136(v=AX.60)
ms:contentKeyID: 62952562
author: tonyafehr
ms.date: 09/17/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RPayCashSheet
- Forms.RPayDepositJournal
- Forms.RPaySheetBankPayment
- Forms.RPaySheetTable
- MsDynAx060.Forms.RPayCashSheet
- MsDynAx060.Forms.RPayDepositJournal
- MsDynAx060.Forms.RPaySheetBankPayment
- MsDynAx060.Forms.RPaySheetTable
- advance pay sheet
- aggregate pay sheet
- cash payment
- closing deposits
- interim pay sheet
- pay sheet
- pay sheets
- payroll pay sheet
- transfer salary payment
- uncollected salaries
- vacation pay sheet
- tax pay sheet
- register deposit
audience: Application User
ms.search.region: Russia
---

# (RUS) Issue payments to workers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create pay-sheets for employees, issue salary payments by cash or by bank transfer, and deposit uncollected employee salaries.

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
<td><p>Related setup tasks</p></td>
<td><ul>
<li><p>Configure staff administration information for workers. For more information, see <a href="rus-configure-staff-administration-information-for-workers.md">(RUS) Configure staff administration information for workers</a>.</p></li>
<li><p>Set up the organizational information. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Create a worker. For more information, see <a href="rus-create-a-worker.md">(RUS) Create a worker</a>.</p></li>
<li><p>Create payroll journals, calculate average earnings, calculate salaries, calculate funds, and create a salary journal. For more information, see <a href="rus-generate-pay-statements.md">(RUS) Generate pay statements</a>.</p></li>
<li><p>Set up vacation types and calculation methods for vacations. For more information, see <a href="rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md">(RUS) Set up vacations, business trips, and incentives for the payroll process</a>.</p></li>
<li><p>Configure the pay-sheet parameters. For more information, see &quot;Set up parameters for salary payments&quot; in <a href="rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md">(RUS) Set up payments, journals, and deductions for the payroll process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Create pay-sheets for advance, vacation, interim, aggregate, tax, and payroll types

Use the **Pay-sheets** form to create pay-sheets for employees. You can create pay-sheets for advance, vacation, tax, interim, aggregate, and payroll types.

## Create a pay-sheet for advance payment

You can create an advance pay-sheet to determine the advance payment that is to be made to certain employees in the middle of a payroll period. The calculation procedure for advances must be configured to calculate the amount to be paid in advance. For more information, see [(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md).

To create an advance pay-sheet, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Pay-sheets** .

2.  In the **Reporting period** field, select the payroll period.

3.  In the **Payroll type** field, select **Advance** to select advance transactions that are created by the payroll calculation procedure during the specified calculation period. For more information, see "Calculate salaries using calculation procedures" in [(RUS) Generate pay statements](rus-generate-pay-statements.md).

4.  Click **Create** to open the **Generation of pay-sheets** form to create an advance pay-sheet.

5.  In the **Level of detailing of pay sheet** field, select either **By enterprise** to create the pay-sheet for the enterprise or **By departments** to create a pay-sheet for each department.

6.  Click **OK** to open the **Generation of pay-sheets** form, and then specify the criteria to generate the advance pay-sheet.

7.  Click **OK** to return to the **Pay-sheets** form. The advance payment values are retrieved from a payroll transaction list that is created for the specified calculation period.

8.  Click **Due** to open the **To cash for timely payment** form.

9.  In the **Start date** and **Expiry date** fields, enter the period, and then click **OK** to update the status of the pay-sheet as **For payment** in the **Payment of pay-sheet** form.

10. Click **Print** to print the payroll and total payroll reports. For more information, see [(RUS) Payroll accounting reports](rus-payroll-accounting-reports.md).

## Create a vacation pay-sheet

You can create a vacation pay-sheet for employees who have registered for paid vacation. For more information about registering and calculating the vacation payment, see [(RUS) Register and calculate compensation for vacations and business trips](rus-register-and-calculate-compensation-for-vacations-and-business-trips.md). The calculated vacation payments are displayed in the **Vacation pay-sheets** form.

To create a vacation pay-sheet, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Pay-sheets** .

2.  In the **Reporting period** field, select the payroll period.

3.  In the **Payroll type** field, select **Vacations**, and then click **New** to create a vacation pay-sheet.

4.  On the **General** tab, select the **Withholding tax** check box to indicate that the vacation payment amount is taxable income.

5.  On the **Payroll content** tab, click **Append** to open the **Vacations to add to pay-sheet** form to add the employee who has registered for paid vacation.

6.  Select the employee, and then click **Append** to create the vacation pay-sheet for the selected employee.

7.  Click **Due** to open the **To cash for timely payment** form.

8.  In the **Start date** and **Expiry date** fields, enter the period, and then click **OK** to update the status of the pay-sheet as **For payment** in the **Payment of pay-sheet** form.

9.  Click **Print** to print the payroll and total payroll reports. For more information, see [(RUS) Payroll accounting reports](rus-payroll-accounting-reports.md).

## If required: Correct a vacation pay-sheet

You can update a vacation pay-sheet that is created with incorrect information before the payment is made to the employee.

To correct a vacation pay-sheet, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Vacations** \> **Vacation registration**.

2.  On the **Overview** tab, select the employee for whom the pay-sheet correction must be made.

3.  Clear the **Add to salary** check box to exclude the vacation payment for the selected employee from the payroll.

4.  On the **Calculation** tab, in the **Amount** field, enter the amount to be updated.

5.  On the **Overview** tab, select the **Add to salary** check box to include the vacation payment in the payroll list.

6.  Repeat steps 1 through 7 from “Create a vacation pay-sheet”.

## Create a tax pay-sheet

You can create a tax pay-sheet for employees to determine the tax refunds that must be paid to the employees. A tax pay-sheet is applicable only for employees from whom excess tax was deducted. The excess tax amount will be refunded back to the employees by bank transfer. Before you create a tax pay-sheet, you must select **Tax refund via separate pay-sheet** in the **Reimbursement method** field in the **Tax calculation settings** form. For more information, see "Set up parameters for tax calculations" in [(RUS) Set up taxes and funds for the payroll process](rus-set-up-taxes-and-funds-for-the-payroll-process.md).

To create a tax pay-sheet, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Pay-sheets** .

2.  In the **Reporting period** field, select the payroll period.

3.  In the **Payroll type** field, select **Tax** to display all of the transactions that are created by the predefined payroll calculation procedure for tax refund in the specified calculation period.

4.  Click **Create**. The tax refund amount values are retrieved from the payroll transaction list that is created for the specified calculation period. The status of the payroll is **In process**.

5.  Click **Due** to open the **To cash for timely payment** form.

6.  In the **Start date** and **Expiry date** fields, enter the period, and then click **OK** to update the status as **For payment** in the **Payment of pay-sheet** form.

7.  Click **Print** to print the payroll and total payroll reports. For more information, see [(RUS) Payroll accounting reports](rus-payroll-accounting-reports.md).

## Create an interim pay-sheet

You can create an interim pay-sheet to pay an employee in the middle of a month before the organization generates regular payroll for the month. Interim pay-sheets are created automatically or manually for employees who resign or for temporary employees who are employed based on rules that are regulated by the Civil code. Before you create an interim pay-sheet, you must specify the interim period in the **Payroll parameters** form. For more information, see [(RUS) Set up parameters for the payroll process](rus-set-up-parameters-for-the-payroll-process.md).

## Create an interim pay-sheet manually

To create an interim pay-sheet manually, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Pay-sheets** .

2.  In the **Reporting period** field, select the payroll period.

3.  In the **Payroll type** field, select **Interim**, and then click **New** to create an interim pay-sheet.

4.  On the **General** tab, select the **Withholding tax** check box to indicate that the interim payment amount of the employee is taxable.
    

    > [!NOTE]
    > <P>This field is available for modification only for manually created interim pay-sheets.</P>



5.  On the **Payroll content** tab, click **New** to add the employee details.

6.  In the **Amount** field, enter the interim payroll amount and in the **Tax amount** field, enter the income tax amount that is to be paid to the tax authority.

7.  Optional: click **Amount**, and enter an amount to update the same amount for a group of employees.

8.  Click **Due** to open the **To cash for timely payment** form.

9.  In the **Start date** and **Expiry date** fields, enter the period, and then click **OK** to update the status of the pay-sheet as **For payment** in the **Payment of pay-sheet** form.

10. Click **Print** to print the payroll and total payroll reports. For more information, see [(RUS) Payroll accounting reports](rus-payroll-accounting-reports.md).

## Create an interim pay-sheet automatically

To create an interim pay-sheet automatically, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Pay-sheets** .

2.  In the **Reporting period** field, select the payroll period, and in the **Payroll type** field, select **Interim**.

3.  Repeat steps 4 through 10 from “Create pay-sheet for advance payment”.

## Create an aggregate pay-sheet

An aggregate pay-sheet is a collection of payroll pay-sheets and interim pay-sheets. You can create an aggregate pay-sheet to reduce the number of pay-sheets that are created separately for the interim and payroll pay-sheets.

## Create an aggregate pay-sheet manually

To create an aggregate pay-sheet manually, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Pay-sheets** .

2.  In the **Reporting period** field, select the payroll period.

3.  Click **Query** to specify the criteria to use to generate the pay-sheet content automatically.

4.  On the **Payroll content** tab, in the **Payroll type** field, select **Aggregate**, and then click **New** to create an aggregate pay-sheet.

5.  Repeat steps 4 through 10 from “Create an interim pay-sheet manually”.

## Create an aggregate pay-sheet automatically

To create an aggregate pay-sheet automatically, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Pay-sheets** .

2.  In the **Reporting period** field, select the payroll period, and in the **Payroll type** field, select **Aggregate**.

3.  Repeat steps 4 through 10 from “Create pay-sheet for advance payment”.

## Create a payroll pay-sheet

You can create a payroll pay-sheet at the end of the month or at the end of the calculation period to make salary payments for employees.

To create a payroll pay-sheet, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Pay-sheets** .

2.  In the **Reporting period** field, select the payroll period.

3.  In the **Payroll type** field, select **Payroll** to select the transactions that are created by the predefined payroll calculation procedure for the specified calculation period. For more information, see "Create and post a payroll journal" in [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## 2\. Issue payments to an employee by cash or by bank transfer

You can issue payments for a pay-sheet either by cash or by bank transfer.

## Issue payments for the generated pay-sheet by cash

To issue payments for the generated pay-sheet by cash, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Payment of pay-sheet** .

2.  In the **View** field group, click **Due** to view the payroll records that are in the **For payment** status.

3.  On the **Payroll content** tab, verify the employees who are included in the payroll for cash payment.

4.  In the **Payment of pay-sheet** form, click **To pay**, and then specify the payment date.

5.  Click **OK**. A cash journal is automatically generated with cash payment slips. The cash payment slip contains the payment amount paid to the employee through cash.
    
    On the **General** tab, you can view the cash payment slip number and the date of the generated payment slip.

## Issue payments for the generated pay-sheet by bank transfer

Use the **Payments via bank** form to pay the salary of an employee through bank transfer.

To provide payment details to a bank, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Payment of pay-sheet** .

2.  In the **View** field group, click **Due** to view the payroll records that have been set to **For payment** status.

3.  On the **Payroll content** tab, view the employees who are included in the payroll.

4.  On the **Payment via bank** tab, select the **Bank payment** check box for those employees who can collect their salaries through bank transfer.

5.  Click **Pass into a bank** to provide employee payment details that are selected on the **Payment via bank** tab. The employee’s bank account details are displayed.

To pay the salary of an employee through a bank, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Payments via bank**.

2.  Select the payroll, and then click **Functions** \> **Create journal** to open the **Bank payment** form.

3.  In the **Bank payment** form, enter the payment date in the **Date of payment** field, and then click **OK**. A journal is automatically generated and the amount is paid via bank transfer.
    

    > [!NOTE]
    > <P>The journal details are available on the <STRONG>General</STRONG> tab.</P>



4.  Optional: Click **Functions** \> **Delete journal** to delete the journal before the journal is posted.

5.  Optional: Click **Inquiries** \> **Pay-sheets** to inquire about the related pay-sheet.

6.  Click **Functions** \> **Post** to post the salary journal. On the **Payment via bank** tab, the **Posted** check box is selected automatically after you post the journal.

## 3\. Optional: Register and close deposits

Salaries are registered as deposits when they are not paid to employees for specific reasons. For example, when the legal entity has insufficient funds in their bank account, or when the employee's bank account code is not known.

These deposits are written against the profit of the legal entity if the deposits are not claimed by the employee for a specific period.

## Register and pay deposits for an employee’s salary

To register and pay deposits for salaries, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Payment of pay-sheet** .

2.  In the **View** field group, click **Due** to view the payroll records that have been set to **For payment** status.

3.  On the **Payroll content** tab, select an employee, and then select the **Deposit** check box for the employees for whom you want to deposit salary amounts.

4.  Click **Pass to the deposit** to transfer the employee records to the **Deposit** tab.

5.  On the **Deposit** tab, select the employee records, and then click **Deposit**.

To pay the deposits using the deposits forms, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Deposit** \> **Register of deposits**.

2.  Select the deposit line, and then click **Deposit** to make the payments for the selected deposit.

3.  If required: Click **Pay** \> **Via cash module** to make the payment for the selected deposit using cash payments.
    
    –or–
    
    Click **Pay** \> **Against payroll** to add the payment amount to the current payroll pay sheet of the employee.

## Closing deposits against profit

Use the **Deposits** form to close the deposits of employees if no deposits have been paid for a specific period. In the **Deposit closing against profit** form, enter a date to close the deposits that are uncollected by the employee or unpaid by the employer until the entered date.

To close the deposits using the **Deposit closing against profit** form, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Deposit** \> **Deposit closing against profit**.

2.  Enter a date to close the deposits that are uncollected by the employee or unpaid by the employer until the entered date.

To close the deposits using the **Deposits** form, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Deposit** \> **Register of deposits**.

2.  Select deposit lines, and then click **Pay** \> **Against profit** to write off the deposit lines against the profit of the legal entity.

## Next step

After issuing payments to employees, you can manage the tax settlements for each branch, including details about taxpayers. For more information, see the [(RUS) Settle tax liabilities](rus-settle-tax-liabilities.md).

## Related tasks

[(RUS) Create and post a vacation resolution](rus-create-and-post-a-vacation-resolution.md)

[(RUS) Create and post a business trip resolution](rus-create-and-post-a-business-trip-resolution.md)

[(RUS) Create and post an incentive resolution](rus-create-and-post-an-incentive-resolution.md)

[(RUS) Register and calculate compensation for vacations and business trips](rus-register-and-calculate-compensation-for-vacations-and-business-trips.md)

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
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p><strong>Payroll administrator</strong></p></li>
<li><p><strong>Payroll manager</strong></p></li>
</ul>
<p>To issue payments to workers, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Issue payments to workers</strong> (PayrollIssueWorkerPaymentsMaintain)</p></li>
<li><p><strong>Inquire into payments to workers</strong>(RPayWorkerInquire)</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To issue payments to workers, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Maintain pay sheets (all)</strong></p></td>
<td><p>RPayAllPaySheetsMaintain</p></td>
<td><p>Create a pay-sheet.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain deposited payroll</strong></p></td>
<td><p>RPayDepositMaintain</p></td>
<td><p>Close deposits for workers.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View and update vacation pay-sheets</strong></p></td>
<td><p>RPayPaySheetView</p></td>
<td><p>Create a cash payment for a pay-sheet and register a deposit.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


