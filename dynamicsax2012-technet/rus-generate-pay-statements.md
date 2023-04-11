---
title: (RUS) Generate pay statements
TOCTitle: (RUS) Generate pay statements
ms:assetid: a4165fe6-422b-4441-9f3d-7116f7503cd7
ms:mtpsurl: https://technet.microsoft.com/library/Dn435955(v=AX.60)
ms:contentKeyID: 56730928
author: tonyafehr
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- salary
- payments
- close
- payment
- funds
- pay
- closing
- Forms.LedgerJournalTable
- payroll journal
- pay statement
- Forms.RPayEmplCalculate
- Forms.RPayJournalTable
- Forms.LedgerJournalTransRPay
- Forms.RPayAverageEarnEmplPeriodTable
- Forms.RPayCalculate
- Forms.RPayCheckPosting
- Forms.RPayJournalTrans
- Forms.RPaySum
- average earnings
- average wage
- payroll journals
- average wages
- salaries
- pay statements
- pays
- salary journal
- salary journals
- salary statement
- salary statements
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate pay statements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to create payroll journals, calculate average earnings, calculate salaries, calculate funds, create a salary journal, and close the payroll period.

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
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Configure staff administration information for workers. For more information, see <a href="rus-configure-staff-administration-information-for-workers.md">(RUS) Configure staff administration information for workers</a>.</p></li>
<li><p>Set up the organizational structure. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Create workers, and then hire, transfer, and dismiss workers. For more information, see <a href="rus-create-a-worker.md">(RUS) Create a worker</a> and <a href="rus-hire-transfer-and-dismiss-a-worker.md">(RUS) Hire, transfer, and dismiss a worker</a>.</p></li>
<li><p>Set up compensations for workers. For more information, see <a href="rus-set-up-employee-compensation-parameters.md">(RUS) Set up employee compensation parameters</a>.</p></li>
<li><p>Set up parameters for the payroll process. For more information, see <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></li>
<li><p>Set up calculation procedures for the payroll process. For more information, see <a href="rus-set-up-calculation-procedures-for-the-payroll-process.md">(RUS) Set up calculation procedures for the payroll process</a>.</p></li>
<li><p>Set up payments, journals, and deductions for the payroll process. For more information, see <a href="rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md">(RUS) Set up payments, journals, and deductions for the payroll process</a>.</p></li>
<li><p>Set up vacations, business trips, and incentives for the payroll process. For more information, see <a href="rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md">(RUS) Set up vacations, business trips, and incentives for the payroll process</a>.</p></li>
<li><p>Set up taxes and funds for the payroll process. For more information, see <a href="rus-set-up-taxes-and-funds-for-the-payroll-process.md">(RUS) Set up taxes and funds for the payroll process</a>.</p></li>
<li><p>Set up income tax information for employees. For more information, see (RUS) Set up the employee income tax information.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Related task</strong></p></td>
<td><ul>
<li><p>Manage the workforce process. For more information, see <a href="rus-support-the-workforce-management-process.md">(RUS) Support the workforce management process</a>.</p></li>
<li><p>If required: Create timesheets for workers. For more information, see <a href="rus-create-a-timesheet-for-an-employee.md">(RUS) Create a timesheet for an employee</a>.</p></li>
<li><p>If required: Create and calculate standard deductions for borrowing and alimony. For more information, see (RUS) Configure standard deductions calculation.</p></li>
<li><p>If required: Register vacations, business trips, or sick lists, and calculate compensations. For more information, see (RUS) Register vacations, business trips, and calculate compensation.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Create and post a payroll journal

Use the **Payroll journal** and **Payroll journal lines** forms to create a payroll journal and payroll journal lines that are used to create non-recurring accruals and deductions for employees. You can use a payroll journal to register payments that are not processed through other type of entries, such as timesheets, vacations, business trips, sick lists, or bonuses. You can also use a payroll journal to make manual adjustments to the values that are automatically calculated for other processes. You can create lines in a journal for specific employees or for groups of employees.

To create and post a payroll journal, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Payroll journal** \> **Payroll journal**.

2.  Click **New** or press CTRL+N to create a journal.

3.  In the **Name** field, select the identification code for a payroll journal name.

4.  On the **General** tab, select the **Use rate value per employee** check box to use the date effective rate value that you specified for each employee or group in the **Value** field on the **Overview** tab in the **Set up rate values** form. If you clear this check box, the default rate value that you specified for the rate in the **Value** field on the **Value** tab in the **Rates** form is used for all of the employees or groups.

5.  In the **Number of incentive resolution** field, select the number of the incentive resolution order that is related to the payroll journal. Click **From order** to create journal lines automatically based on the information that is available in the selected incentive resolution, such as the pay type code from the resolution type, or the employees that have incentive amounts from the resolution lines.

6.  Specify values in other fields, if required, and then click **Lines**.

7.  In the **Payroll journal lines** form, click **New** or press CTRL+N to create a payroll journal line, and then specify the line type, pay type, quantity, rate, and amount for the line.
    
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
    <td><p><strong>Date</strong></p></td>
    <td><p>Select the transaction date for the journal line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Line type</strong></p></td>
    <td><p>Select the type of line.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Employee</strong> – Create the journal line for an employee.</p></li>
    <li><p><strong>Group</strong> – Create the journal line for a payroll group.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you select this option and create a payroll journal line, then the same payroll line, pay type, and amount are created for all of the employees in the group when you post the journal.</P>


    </div></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Code</strong></p></td>
    <td><p>Select the identification code for an employee or a payroll group code, depending on the line type that you select.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Pay type</strong></p></td>
    <td><p>Select a pay type for which an accrual or deduction is to be entered. The <strong>Description</strong> field is updated with the description of the pay type. You can modify the description.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The <STRONG>Qty</STRONG>, <STRONG>Rate</STRONG>, <STRONG>Percent</STRONG>, and <STRONG>Amount</STRONG> fields are available based on the information that you set up for the pay type in the <STRONG>Pay type setup</STRONG> form. For more information, see “6. Set up pay types” in <A href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</A>.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Qty</strong></p></td>
    <td><p>Enter the number of units for the line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rate</strong></p></td>
    <td><p>Enter the per unit rate that applies to the journal line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Percent</strong></p></td>
    <td><p>A selected check box indicates that the rate is specified as a percent value.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount</strong></p></td>
    <td><p>Enter the accrual or deduction amount for the journal line.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If the <STRONG>Qty</STRONG> and <STRONG>Rate</STRONG> fields are updated, the amount is automatically calculated and updated in the <STRONG>Amount</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name of person</strong></p></td>
    <td><p>If the deduction code of the income code for the pay type that you select for the journal line is associated with an employee relative, select the name of the relative.</p></td>
    </tr>
    </tbody>
    </table>


8.  Click **Validate**, and then click **OK** to validate the journal lines.

9.  Click **Print** to print the journal report, if required.

10. Click **Post**, and then click **OK** to post the journal lines.

You can click **Reverse** in the **Payroll journal** or **Payroll journal lines** form to cancel the posting of the journal in the same period in which you posted the journal. You can click **Adjust storno** in the **Payroll journal** or **Payroll journal lines** form to process the storno adjustment for the selected payroll journal in the period following the posting period. You can click **View the storno** in the **Payroll journal** or **Payroll journal lines** form to inquiry the storno adjustment for the selected payroll journal.

## 2\. Calculate the average wages that are earned by a worker

Use the **Employee average earnings calculation** form to calculate the average earnings of an employee. You can calculate different types of salary accruals using the average earnings method. These can include per diem expenses, travel allowances, gifts, annual bonuses, vacations, and sick lists.

You can use multiple methods to calculate the different average earnings accrual types.

Microsoft Dynamics AX can also calculate the average earnings automatically if you configure it in the counters that are running. For more information about how to set up counters, see “4. (RUS) Set up counters for calculation sequences” in [(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md).

To calculate the average wages that are earned by a worker, follow these steps:

1.  Click **Payroll (Russia)** \> **Average earnings calculation** \> **Average earnings calculation lines**.

2.  In the **Employee average earnings calculation** form, in the **Reporting period** field, modify the calculation period, if required. This field displays the current calculation period by default

3.  To create a calculation line manually, perform the following steps:
    
    1.  Click **New** or press CTRL+N to create a line.
    
    2.  In the **Calculation method code** field, select the identification code of the calculation method to use for the line.
    
    3.  In the **Employee** field, select the identification code of the employee to calculate average earnings for. You must select an employee for whom you have defined a working schedule.
    
    –or–
    
    To create calculation lines using a query, perform the following steps:
    
    1.  Click **Add lines** to open the **Average earnings calculation line creation** form.
    
    2.  In the **Calculations** field, select the identification code for the average earnings calculation method to create calculation lines for.
    
    3.  Click **Select**, and then specify additional criteria to create calculation lines, if required. Click **OK** to create calculation lines in the **Employee average earnings calculation** form.

4.  In the **Number of month** field, select the identification code for a rate that contains the number of months for the average earnings calculation period.

5.  In the **Working week duration** field, select **5 days**, **6 days**, or **7 days** as the duration of the work week.

6.  On the **General** tab, specify calculation methods, numerical parameters, time parameters, and bonus parameters.
    
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
    <td><p><strong>Calculation method of short month</strong></p></td>
    <td><p>Select the calculation method for the days or hours that are worked and apply it to each month within the average earnings calculation period during which the employee did not work for the full month.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Summary</strong> – The number of days or hours that are worked is calculated using resulting information about the employee days or hours that are worked for the month:</p>
    <p>The days or hours that are available to work according to the schedule - The days or hours that the employee is absent.</p></li>
    <li><p><strong>Calendar</strong> – The number of days or hours that are worked is calculated using the daily timesheet and calendar details:</p>
    <p>((The days or hours according to the schedule - The days or hours that the employee is absent) / The number of calendar days in the month) * The average number of days in the month.</p></li>
    <li><p><strong>By coefficient</strong> – The number of days or hours that are worked is calculated using the resulting information from the number of employee days or hours that are worked for the month, the actual time that is worked considering the conversion factor that is set for the calendar of the employee, and the working week duration.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calculation method of full month</strong></p></td>
    <td><p>Select the average earnings calculation method for the days or hours that are worked, and apply it to each month within the average earnings calculation period that the employee worked for the entire month.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>According to calendar</strong> – The number of days or hours in the calculation period according to the working schedule.</p></li>
    <li><p><strong>Average value</strong> – The average number of days or hours per month.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Calculation type</strong></p></td>
    <td><p>Select <strong>By days</strong> or <strong>By hours</strong> to calculate average daily or hourly earnings.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you select <STRONG>Calendar</STRONG> in the <STRONG>Calculation method of short month</STRONG> field, you must select <STRONG>By days</STRONG> in this field.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Base of calculation</strong></p></td>
    <td><p>Select the identification code for the average earnings calculation base. The base includes pay types that are used in the average earnings calculation.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Average earnings base</strong></p></td>
    <td><p>Select the identification code for the average earnings calculation base. The base includes pay types that are used in the average earnings calculation.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The average earnings base is applied for the average earnings calculation instead of base of calculation when there are no accruals available for previous calculation periods that are included in the base of calculation.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Step-up ratio</strong></p></td>
    <td><p>Select the rate that contains the ratio to index the average earnings during the calculation period.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>According to schedule</strong></p></td>
    <td><p>Select a time group that defines the work time according to the schedule.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Actually worked</strong></p></td>
    <td><p>Select a time group that defines the time that was actually worked.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>By coefficient</STRONG> in the <STRONG>Calculation method of short month</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Absences from work</strong></p></td>
    <td><p>Select a time group that defines an acceptable reason for an absence from work.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Summary</STRONG> or <STRONG>Calendar</STRONG> in the <STRONG>Calculation method of short month</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>On average</strong></p></td>
    <td><p>Select a time group that defines the time during which the accruals that are entered in the <strong>Average earnings base</strong> field were made.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Bonus base</strong></p></td>
    <td><p>Select a calculation base that includes pay types that correspond with awards that are made for the period from the material incentives fund.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Criteria of bonus accounting</strong></p></td>
    <td><p>Select the criteria to specify the bonus accounting rules in the average earnings calculation.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Maximum</strong> – The applicable number of bonuses that are for the maximum amount are used for the calculation.</p></li>
    <li><p><strong>Minimum</strong> – The applicable number of bonuses that are for the minimum amount are used for the calculation.</p></li>
    <li><p><strong>First</strong> – The applicable number of bonuses that are accrued first are used for the calculation</p></li>
    <li><p><strong>Last</strong> – The applicable number of bonuses that are accrued last are used for calculation.</p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>If the number of bonuses for a single reason exceeds the number that is allowed for the average earnings calculation, a single bonus is selected for the period, depending on the selected criteria. One twelfth of the bonus for the year prior to the event is included in each month that is entered in the average earnings calculation.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Proportional calculation</strong></p></td>
    <td><p>Select this check box to indicate that bonuses are included in the average earnings calculation in proportion to the days or hours worked.</p></td>
    </tr>
    </tbody>
    </table>
    
    The average earnings for the employee are updated in the **Average earnings** field.

7.  On the **Calculation** tab, perform the following steps:
    
    1.  Click **New** or press CTRL+N to open the **Salary Report** form.
    
    2.  In the **Calculation period** field, select the month and year of the calculation period.
    
    3.  In the **Payment source** field, select **Wage fund** or **Incentive fund** as the source of the payments for the amount that is accrued.
    
    4.  Click **OK** to add new lines on the **Calculation** tab.
    
    5.  In the **Days** field, enter the number of working days in a month for the selected employee.
    
    6.  In the **Amount** field, enter the amount that is accrued for the calculation of average earnings.
        

        > [!NOTE]
        > <P>The average daily earnings for each calculation line for the selected employee are displayed in the <STRONG>Average per day</STRONG> field. The total average daily or hourly earnings for all calculation lines for the selected employee are displayed in the <STRONG>Average earnings</STRONG> field based on the calculation type.</P>

    
    7.  Click **Recalculation** to recalculate the average earnings wages of an employee if additional accruals were made for the employee.
        

        > [!NOTE]
        > <P>If you modify the values in the <STRONG>Days</STRONG> and <STRONG>Amount</STRONG> fields, these modifications are not saved after recalculation.</P>

    
    8.  Click **Hours worked accounting** to open the **Resulting information about employee worked hours** form, where you can view the details about the working days and hours of the employee for the selected calculation period. Close the form.
    
    9.  Click **Bonus** to open the **Bonus** form, where you can view the bonus details for the calculation of the average earnings of an employee. You can view all of the bonuses that are accrued by an employee during the selected calculation period. The **Included** check box is selected for the accruals from incentive funds that are related to the current average earnings incentive calculation for an employee. Close the form.
    
    10. Click **Payroll lines** to open the **Pay type transaction list** form, where you can view the employee accruals for the selected calculation period. The **Included** check box is selected for the accruals from wage funds that are related to the current average earnings wages calculation for an employee.

## 3\. Calculate salaries using calculation procedures

You can calculate salaries that include the payable amounts and the deductions by types of salary, funds, data for medical certificates, and vacations. You can use the data in the working time calculation table, salary journals, and periodic payments according to the configured algorithms or sequences of calculations to calculate the salaries. You can calculate earnings for an employee or all of the employees at once using one or all of the calculation methods.

You can set up the sequence of the calculation procedures in the **Calculation procedures** form.

When you change the input data by entering new pay lines, tables, or medical certificates for a calculation procedure, a message is displayed stating that you must repeat the calculation of all of the dependent procedures. To save calculation time, you can save only the most recent modifications by calculating the pay only for those employees for whom the data have changed.

To calculate salaries using calculation procedures, follow these steps:

1.  Click **Payroll (Russia)** \> **Payroll calculation** \> **Procedure calculation**.
    

    > [!NOTE]
    > <P>The form displays a list of all of the calculation procedures that are specified in the module settings, with an indication of their calculation status.</P>



2.  In the **Status** field, the current status of the procedure is displayed. You can modify the status for the procedure. Use the information in the following table to decide the status of the procedure.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Status</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Not calculated</strong></p></td>
    <td><p>The calculation of the given procedure has not been calculated, or its results are no longer up to date. Modify the status to <strong>Not calculated</strong> when you recalculate the procedure, so that all of the calculations for the procedure and all of the dependent procedures are recalculated.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calculated</strong></p></td>
    <td><p>The procedure has been fully calculated. This option is updated automatically for the calculated procedure.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Exclude</strong></p></td>
    <td><p>The procedure is excluded from the calculation.</p></td>
    </tr>
    </tbody>
    </table>
    
    If you change the status of a procedure, the statuses of the child procedures also change. For example, the advance calculation requires a previous vacation payment calculation. When you set the status of the vacation payment calculation procedure to **Not calculated**, the same status is assigned to the advance calculation procedure. In the **Modified date and time** field, the date and time of the last payroll calculation are displayed for the corresponding procedure. The **Modified by** field displays the identification code of the user who ran the last calculation for this procedure.

3.  On the **General** tab, in the **Payment period** and the **Accrual date** fields, the payment period and the accrual date for the current calculation procedure are updated.

4.  Select the **Accrual date - current calculation date** check box to indicate that the date of the current calculation is updated in the calculated payroll lines for the selected calculation procedure.

5.  To process the calculation of a procedure that has a status of **Not calculated**, select the procedure on the **Overview** tab, and then click **Calculation**. Specify the criteria, and then click **OK**.
    
    Alternatively, to process calculations for all of the procedures that have a status of **Not calculated**, click **Calculate all**.

6.  Click **Payroll lines** to open the **Payments and deductions registration** form, where you can view the results of the calculation of the current procedure.

## 4\. Verify worker payments and deductions

Use the **Payments and deductions registration** form to verify payroll calculation results and register payments and deductions for a worker.

To verify worker payments and deductions, follow these steps:

1.  Click **Payroll (Russia)** \> **Queries** \> **Payments and deductions**.

2.  In the **Payments and deductions registration** form, in the left pane, a list of company employees is displayed.

3.  In the left pane, select an employee. The details about the accruals and deductions of the employees for the calculation period are updated in the right pane.

4.  To register a payment or deduction correction for an employee, select the employee in the left pane, and then in the right pane, click **New** to create a correction record. The current calculation period and identification code of the employee are updated in the **Corrected period** and **Employee** fields.

5.  Specify the pay type, amount, department, line values, account, and dimensions codes for the payment or deduction.
    
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
    <td><p><strong>Pay type</strong></p></td>
    <td><p>Select the pay type for the payment or deduction. The name of the pay type is updated in the <strong>Name</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount</strong></p></td>
    <td><p>Enter an amount to pay or deduct.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Department code</strong></p></td>
    <td><p>Select the department code for the selected employee.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Accrual date</strong></p></td>
    <td><p>Select the actual date of the accrual.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Payment period</strong></p></td>
    <td><p>Select the month and year of the period for which the payment or deduction is processed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Hours</strong></p></td>
    <td><p>Enter the number of hours for the pay type transaction.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Days</strong></p></td>
    <td><p>Enter the number of days for the pay type transaction.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Account type</strong></p></td>
    <td><p>Select the type of account for the pay type transaction that specifies the type of account that the transaction is applied to.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Account</strong></p></td>
    <td><p>Select the account for the pay type transaction.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name of person</strong></p></td>
    <td><p>If the payment or deduction is associated with an employee relative, select the name of the relative.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Paid</strong></p></td>
    <td><p>The difference between the total amount of accruals and the total amount of deductions.</p>
    <div class="alert">

    > [!NOTE]
    > <P>When you generate the pay sheet for payroll, the value in this field is transferred to the line.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


6.  Click **Calculation** to calculate or recalculate procedures for the selected employee. After the calculation is completed, the details in the form are automatically updated.

You can also generate the following reports to verify the payments and deductions:

  - **Income sheet** report – This report contains the payments that are made for each pay type for a calculation period. Click **Payroll (Russia)** \> **Reports** \> **Income sheet**.

  - **Retention sheet** report – This report contains the deductions that are made for each pay type for a calculation period. Click **Payroll (Russia)** \> **Reports** \> **Retention sheet**.

  - **Payments and deductions** report – This report contains a pivot table that you can use to view details about the payments and deductions that are made for a calculation period. For example, you can view the amount that is paid in the calculation period; you can view the amount, days, or hours for each employee, or for all of the employees; or you can view the payment and deduction amounts for employees based on pay types, departments, and other factors. Click **Payroll (Russia)** \> **Reports** \> **Pivot tables** \> **Pay type transaction list**.

## 5\. If required: Recalculate salaries based on the latest modifications to the data

If you make changes to the employee data after completing payroll calculation for the employees, you can use the **Recent transactions** form to view the employees for whom you made changes, and recalculate the salaries for these employees. You can make changes such as specify additional accruals and deductions in the working time registration table or make changes to the average earnings, vacations, or sick time.

To recalculate salaries based on the latest modifications to the data, follow these steps:

1.  Click **Payroll (Russia)** \> **Payroll calculation** \> **Recent transactions**.

2.  In the **Recent transactions** form, the list of employees for whom additional accruals or deductions have occurred in the current payment period are displayed. In the **Procedure code** and **Name** fields, the identification code and name of the calculation procedures to be recalculated are displayed.

3.  To recalculate the salary for an employee, select the employee record, and then click **Recalculate current**. Alternatively, to recalculate the salaries for all of the employees that are listed, click **Recalculate all**.

## 6\. Calculate taxes and funds

You can generate the tax base values and calculate accrued individual income tax deductions and off-budget funds contributions. When you calculate taxes and funds, Microsoft Dynamics AX uses the results of the payroll calculation and processes the data for all of the employees within a legal entity. You can calculate taxes and funds only after you calculate all of the payroll procedures, and there are no recently changed transactions available with a status of **Not calculated**.

To calculate taxes and funds, follow these steps:

1.  Click **Payroll (Russia)** \> **Payroll calculation** \> **Data and funds calculation**.

2.  Microsoft Dynamics AX runs the calculation of taxes and funds for the current period.
    

    > [!NOTE]
    > <P>The taxes and funds can only be calculated if the current calculation date is the last in the current calculation period.</P>



3.  Click **Payroll (Russia)** \> **Periodic** \> **Data for income tax calculation**.

4.  Microsoft Dynamics AX runs the calculation of accrued individual income taxes for all employees for the current period

You can use the following forms and reports to verify the calculated taxes and off-budget funds:

  - **Income tax** form – This form displays the income tax totals for each employee. Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Income tax**.

  - **Payments to off-budget funds (totals)** form – This form displays the total amount of off-budget funds for all of the branches for each employee. Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Funds totals**.

  - **Income tax totals** form – This form displays the total amount of taxes for all of the branches for each employee. Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Income tax totals**.

  - **Off-funds allocations (in income types)** report – This report contains the amounts that are allocated to each off-budget fund for each pay type in a calculation period. Click **Payroll (Russia)** \> **Reports** \> **Off-funds allocations (in income types)**.

  - **Off-funds allocations (in accounts)** report – This report contains the amounts that are allocated to each off-budget fund for each account in a calculation period. Click **Payroll (Russia)** \> **Reports** \> **Off-funds allocations (in accounts)**.

## 7\. Create and post a salary journal

Use the **Salary journal** and **Journal voucher** forms to create and post a salary journal. After you create a salary journal for the current pay period, you cannot make changes in pay statements for that period. You can modify or delete the lines of a salary journal, although doing this is not recommended because it can cause deviations from the pay sheets, fund data, and tax registers. You can verify a journal before you post it. After you post the salary journal, you cannot make any changes to it. You can create a journal that contains reversed transactions for a posted journal.


> [!NOTE]
> <P>You can create a salary journal only if you complete the calculation of payroll, taxes, and funds for the current period.</P>



To create and post a salary journal, follow these steps:

1.  Click **Payroll (Russia)** \> **Payroll calculation** \> **Salary journal**.

2.  In the **Salary journal** form, click **Create** \> **Create journal** to create a journal and journal lines. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).
    

    > [!NOTE]
    > <P>The <STRONG>Create journal</STRONG> button is available only if you complete the calculation of payroll, taxes, and funds for the current period.</P>



3.  Click **Lines** to open the **Journal voucher** form, where you can view and modify the lines for the salary journal. For more information, see [Journal voucher - General journal (form)](https://technet.microsoft.com/library/aa591466\(v=ax.60\)). Close the form.

4.  In the **Salary journal** form, click **Post** \> **Preview journal transactions** to open the **Preview journal transactions** form, where you can view the details that are related to sales tax for each journal line, such as sales tax code, sales tax group, and item sales tax group. Close the form

5.  Click **Validate** \> **Validate** to validate the journal lines.
    

    > [!NOTE]
    > <P>You can also use the <STRONG>Distribution control</STRONG> form to view the relationship between pay types and accounting entities, such as accounts and dimensions that are based on the posting profile configuration. If there are any incorrect entries, you can correct them before posting the journal. Click <STRONG>Payroll (Russia)</STRONG> &gt; <STRONG>Queries</STRONG> &gt; <STRONG>Distribution control</STRONG>.</P>



6.  Click **Post** \> **Post** to post the journal.

You can click **Create** \> **Reverse journal** in the **Salary journal** form to reverse the accounting transactions of a posted journal. A journal that contains a reversal of the lines from the original journal is automatically created in the **Salary journal** form.

## 8\. Close a payroll period

After you calculate the payroll, taxes, and funds; create and post a salary journal; create salary pay sheets; and transfer salary payments; use the **Close the salary** form to close a payroll period. If you do not create pay sheets, a message is displayed that you must create pay sheets before closing the period. When you close a period, Microsoft Dynamics AX performs the following tasks:

  - Calculates debts of the employer and employees, and generates payroll lines for the amounts that have corresponding payroll types.

  - Changes the status of the calculation procedures to **Not calculated** in the **Calculation procedures state** form.

  - Changes the calculation period to the next reporting period. All of the new payroll lines automatically move to the new period.

  - Updates the current calculation date as the next date in the **Calculation calendar** area in the **Payroll parameters** form.

  - Remove payroll period records that are specific to an employee for the new payroll period records.

You cannot make any modifications to a closed period after you perform calculations for the new period. Transaction amounts in the ledger, the bank, and in cash are fixed. However, you can reopen and make changes in a closed period if you have not performed any calculations for the new period. You can make changes, such as reversing and recreating a salary journal after you recalculate the off-budget funds.

You can close the period for all employees or for a specific employee.


> [!NOTE]
> <P>You can close the payroll period only if the current calculation date is the last date in the current calculation period.</P>



To close a payroll period, follow these steps:

1.  Click **Payroll (Russia)** \> **Payroll calculation** \> **Close the salary**.
    

    > [!NOTE]
    > <P>If you have already closed the period, a warning message displays, indicating that the modifications in the closed period cannot take place. If there are no errors in the payroll calculations, respond to this warning with a confirmation.</P>



2.  If required, click **Select** to specify additional criteria, such as employee codes , and then click **OK** to close the period for employees who meet the criteria. Alternatively, to close the period for all of the employees, do not specify any criteria.

3.  In the **Close the salary** form, click **OK** to close the period.

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
<td><p>To generate pay statements, you must be a member of a security role that includes the following duties.</p>
<ul>
<li><p><strong>Enable compensation process</strong> (HcmJobTypeMaintain)</p></li>
<li><p><strong>Set up time management master data</strong> (RPaySetupTimeMasterData)</p></li>
<li><p><strong>Inquire into pay agreement master</strong> (JmgPayAgreementMasterInquire)</p></li>
<li><p><strong>Inquire into time and attendance payroll policies</strong> (JmgTimeAttandancePayrollPoliciesInquire)</p></li>
<li><p><strong>Maintain pay statements</strong> (PayrollPayStatementGenerationMaintain)</p></li>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
<li><p><strong>Inquire into payroll payments</strong> (PayrollPayStatementGenerationInquire)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitProcessInquire)</p></li>
<li><p><strong>Post pay statements</strong> (PayrollJournalizePayStatementMaintain)</p></li>
<li><p><strong>Maintain tax register journals</strong> (RTax25RegisterJournalMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To generate pay statements, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p><strong>Maintain payroll earnings</strong> (RPayAvgPayrollMaintain)</p></li>
<li><p><strong>View pay adjustment pay types</strong> (JmpPayAdjustCostTypeView)</p></li>
<li><p><strong>Close pay statements</strong> (RPayCloseStatements)</p></li>
<li><p><strong>Generate pay statements</strong> (PayrollPayStatementsGenerationProcess)</p></li>
<li><p><strong>Maintain current employees payroll period setting</strong> (RPayEmplPayPeriodMaintain)</p></li>
<li><p><strong>Maintain off-budget funds contributions</strong> (RPayFundsContributionsMaintain)</p></li>
<li><p><strong>Maintain pay statements</strong> (PayrollPayStatementMaintain)</p></li>
<li><p><strong>Maintain pay statements (payroll)</strong> (RPayStatementMaintain)</p></li>
<li><p><strong>Maintain payroll related worker income tax</strong> (RPayIncomeTaxMaintain)</p></li>
<li><p><strong>Maintain payroll tax history</strong> (PayrollTaxHistoryMaintain)</p></li>
<li><p><strong>Maintain salary deductions (alimony)</strong> (RPayDeductionAlimonyMaintain)</p></li>
<li><p><strong>Maintain salary deductions (all)</strong> (RPayDeductionAllMaintain)</p></li>
<li><p><strong>Maintain salary deductions (borrowing)</strong> (RPayDeductionBorrowingMaintain)</p></li>
<li><p><strong>Maintain salary deductions (others)</strong> (RPayDeductionOthersMaintain)</p></li>
<li><p><strong>Maintain tax register report</strong> (PayrollTaxRegisterReportMaintain)</p></li>
<li><p><strong>Recalculate salary deductions</strong> (RPayRecalcDeduction)</p></li>
<li><p><strong>Review income tax calculation summary</strong> (RPayIncomeTaxReview)</p></li>
<li><p><strong>Validate the salary journal</strong> (RPaySalaryJournalValidate)</p></li>
<li><p><strong>View current employees payroll period setting</strong> (RPayEmpPeriodView)</p></li>
<li><p><strong>View salary deductions calculation history</strong> (RPayDeductionHistoryView)</p></li>
<li><p><strong>Process payroll posting</strong> (PayrollJournalizePayStatement)</p></li>
<li><p><strong>Reverse a journal</strong> (LedgerJournalCreateStorno_Reverse_RU)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


