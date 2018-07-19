---
title: (RUS) Set up calculation procedures for the payroll process
TOCTitle: (RUS) Set up calculation procedures for the payroll process
ms:assetid: 1b0755ec-903b-4317-aa43-863748ee7f3d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn435987(v=AX.60)
ms:contentKeyID: 56732188
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- calculation
- payroll
- salary
- payments
- sequence
- counters
- counter
- procedures
- sequences
- payment
- pay
- calculations
- procedure
- average earnings
- salaries
- avereage earning
- calculation method
- calculation methods
- calculation procedure
- calculation procedures
- Forms.RPayAverageEarnEmplTable
- Forms.RPayAverageEarnParameters
- Forms.RPayAverageEarnTable
- Forms.RPayCounterTable
- Forms.RPayModuleGroupTable
- Forms.RPayModuleTable
- Forms.RPaySeqTable
- payroll procedure
- payroll procedures
- MsDynAx060.Forms.RPayAverageEarnEmplTable
- MsDynAx060.Forms.RPayAverageEarnParameters
- MsDynAx060.Forms.RPayCounterTable
- MsDynAx060.Forms.RPayModuleTable
- MsDynAx060.Forms.RPayModuleGroupTable
- MsDynAx060.Forms.RPayAverageEarnTable
- MsDynAx060.Forms.RPaySeqTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up calculation procedures for the payroll process 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to set up calculation procedures, their sequences and counters, and calculation methods to calculate the salaries for workers. You can create calculation procedures to set up the sequences that define the rules and calculation order for the salary calculation of employees. Calculation procedures are processed separately for specific accruals and deductions.

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
<li><p>Create tax registration numbers, social insurance information, and the organizational structure for a legal entity. Create departments in an organization, assign each department to a branch, and reserve a position for a department. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Create a list of time codes for working time, overtime, idle time, vacation, sick leave, and business trips. For more information, see <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
<li><p>Set up vacation types and business trip types, as well as how to set up calculation methods for vacations and business trips. For more information, see <a href="rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md">(RUS) Set up vacations, business trips, and incentives for the payroll process</a>.</p></li>
<li><p>Set up the types of incapacities and injuries, scale of charges, and pay frequencies for employee compensation payments. For more information, see <a href="rus-set-up-employee-compensation-parameters.md">(RUS) Set up employee compensation parameters</a>.</p></li>
<li><p>Set up employee seniority. For more information, see “3. (RUS) Set up the seniority of an employee” in <a href="rus-support-the-workforce-management-process.md">(RUS) Support the workforce management process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a calculation procedure group

Use the **Calculation procedure groups** form to set up a group of calculation procedures. When you create a calculation procedure group, Microsoft Dynamics AX assigns a numeric identification code to the group. The calculation procedures are processed in ascending order of the procedure group numbers. You can use the group numbers to organize the dependent procedures in a hierarchy. For example, you can include the calculation procedures for basic accruals such as basic wages, vacation, and sick pay that are included in the first group. You can include the procedures that are dependent upon the accruals in the second group, procedure to calculate the income tax for private individuals in the third group, and procedures to calculate other deductions, such as fines, borrowings, or alimonies, in the final group.

To set up a calculation procedure group, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Calculation procedure groups**.

2.  Click **New** or press CTRL+N to create a group. Microsoft Dynamics AX automatically updates the next group number in the sequence in the **Group code** field.

3.  In the **Description** field, enter a description for the procedure group.

4.  Click **Calculation procedures** to open the **Calculation procedures** form, where you can create or modify the procedures that are included in the group. For more information, see 2. Set up a calculation procedure.

## 2\. Set up a calculation procedure

Use the **Calculation procedures** form to set up a procedure for payroll calculation. You can also group calculation procedures, and define the order of processing for them. For more information about calculation procedure groups, see 1. Set up a calculation procedure group.

Microsoft Dynamics AX categorizes each calculation procedure as a system procedure or a general procedure. System procedures are automatically created when you select the corresponding configuration keys in Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack. For more information, see Technical information for system administrators. The configuration keys include the following predefined system procedures:

  - Timesheet

  - Contract calculation

  - Employee average earnings calculation

  - Vacation payment calculation

  - Business trip calculation

  - Sick lists

  - Periodical payments

  - Standard deductions

  - Lucre

  - Tax calculations

  - Moonlighters correction

To set up a calculation procedure, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Calculation procedures**.
    
    –or–
    
    Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Calculation procedure groups**. Select a group, and then click **Calculation procedures**.

2.  Click **New** or press CTRL+N to create a calculation procedure. The status of the procedure is updated to **Not calculated** in the **Status** field on the **General** FastTab. Depending on the calculation status of the procedure, this field is updated to **Calculated**. You can also change the status to **Exclude** manually. For more information about calculation procedure statuses, see “3. Calculate salaries using calculation procedures” in [(RUS) Generate pay statements](rus-generate-pay-statements.md).
    

    > [!NOTE]
    > <P>You can view the list of all of the calculation procedure groups, sorted by their group codes on the <STRONG>Calculation order</STRONG> FastTab.</P>



3.  In the **Group code** field, select the numeric identification code of the group for the calculation procedures. The calculation procedures from the same hierarchy are processed in the order of the identification codes of the procedures. The calculation procedures that relate to several groups are calculated sequentially based on the sequence of the numeric identification code of the groups.

4.  In the **Procedure code** and **Name** fields, enter an identification code and a name for the calculation procedure.

5.  On the **General** FastTab, select the **Delete previous calculation** check box to delete all of the data from previous calculations before processing the new calculation. When you calculate procedures for the second and subsequent calculation dates in a calculation period, the salary lines that were calculated on the previous calculation date are deleted, and new salary lines on the current calculation date are created.

6.  In the **Main group code** field, select the main procedure to which the selected sub procedure belongs. The main calculation procedure is not calculated until all of the subordinate procedures are calculated. This helps you define the order of processing for a specific procedure.

7.  Click **Sequences** to open the **Sequence of calculation** form, where you can set up the calculation sequence that defines the calculation order of the values for the pay types and counters. For more information about how to set up sequences for calculation procedures, see 3. Set up sequences for calculation procedures. Close the form.

8.  Click **Query** to specify the calculation criteria for the procedure. Click **OK**.

## 3\. Set up sequences for calculation procedures

Use the **Sequence of calculation** form to set up sequences for a calculation procedure that define the order to calculate the values for the pay types and counters. You can use a particular sequence for only one calculation procedure.

To set up sequences for calculation procedures, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Sequences**.
    
    –or–
    
    Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Calculation procedures**. Click **Sequences**.
    
    –or–
    
    Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Calculation procedure groups**. Select a group, and then click **Calculation procedures**. Click **Sequences**.

2.  In the **Procedure code** field, select the identification code of the calculation procedure to create the sequence for.
    

    > [!NOTE]
    > <P>If you open this form from the <STRONG>Calculation procedures</STRONG> form, the identification code for the selected calculation procedure is automatically updated in this field. You cannot select any other calculation procedure.</P>



3.  Click **New** or press CTRL+N to create a sequence.

4.  The **Sequence** field is automatically updated with the next number in the sequence. You can modify the sequence, if required. When you process a calculation procedure, the sequences that are related to the procedure are calculated in ascending order based on their sequence numbers.

5.  In the **Name** field, enter the name of the calculation sequence.

6.  Click **Counters** to open the **Counter setup** form, where you can set up calculation methods for the selected sequence. For more information about how to set up counters for procedures, see 4. Set up counters for calculation sequences.

7.  Repeat steps 2 through 6 to set up additional sequences.

## 4\. Set up counters for calculation sequences

Use the **Counter setup** form to set up counters for calculation sequences. Counters are structural units of a calculation method for a sequence. You can specify the pay types to use for calculations in the counters. You can enter formulas to calculate pay types in these counters. Counters are calculated according to the calculation method that you select for them. You can also specify the accounting rules that are used to post the results of the calculation. Although you can specify the pay type values manually, the values of the counters are updated while a calculation is processed. The result of the calculation is saved in the counter and is reflected in the pay type.

To set up counters for calculation sequences, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Sequences**. Select a sequence, and then click **Counters**.
    
    –or–
    
    Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Calculation procedures**. Select a calculation procedure, and then click **Sequences**. Select a sequence, and then click **Counters**.
    
    –or–
    
    Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Calculation procedure groups**. Select a group, and then click **Calculation procedures**. Select a calculation procedure, and then click **Sequences**. Select a sequence, and then click **Counters**.
    
    –or–
    
    Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Counters**.
    

    > [!NOTE]
    > <P>When you open the form from this locator, the counter that you create is not attached to a calculation procedure and a calculation sequence. You can use these counters as values for rates of type <STRONG>Counter</STRONG>.</P>



2.  In the upper pane, click **New** or press CTRL+N to create a counter.
    
    If you open the **Counter setup** form from the **Sequence of calculation** form, the **Sequence** field is automatically updated with the number of the sequence that you selected in the **Sequence of calculation** form. The counter is linked with a defined calculation procedure.
    
    If you do not open the **Counter setup** from the **Sequence of calculation** form, the **Sequence** field is updated with 0 (zero).

3.  In the **Counter** and **Name** fields, enter an identification code and name for the counter.

4.  In the **Pay type** field, select the pay type to apply the counter to when the selected counter is used to generate a payroll transaction. You can leave this field blank to use this counter as a subroutine for another counter.

5.  In the lower pane, click **New** or press CTRL+N to create a line, and then specify calculation parameters for the counter line.
    
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
    <td><p><strong>Criteria To</strong></p></td>
    <td><p>Select the condition to calculate the current counter line, depending on the value of the counter that was calculated on the previous line.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>=0</strong></p></li>
    <li><p><strong>&lt;&gt;0</strong></p></li>
    <li><p><strong>&lt;0</strong></p></li>
    <li><p><strong>&gt;0</strong></p></li>
    <li><p><strong>&lt;=0</strong></p></li>
    <li><p><strong>&gt;=0</strong></p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Zero</strong></p></td>
    <td><p>Select this check box to set the value of the current counter to zero when the counter condition that you specify in the <strong>Criteria To</strong> field is true.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Stop</strong></p></td>
    <td><p>Select this check box to stop the calculation of the current counter line when the counter condition that you specify in the <strong>Criteria To</strong> field is true.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Skip</strong></p></td>
    <td><p>Select this check box to skip the current counter line and move to the next counter line in the sequence when the counter condition that you specify in the <strong>Criteria To</strong> field is true.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Line type</strong></p></td>
    <td><p>Select the line type to apply the counter to. The options that you can select in the <strong>From</strong> and <strong>To</strong> fields depend on the line type that you select. Some of the line types are available for system procedures, such as days and hours from the employee working schedule and values of rates and counters. Some of the line types are specific to a general procedure and are available only for the general procedure, such as days and hours for a timesheet procedure and income and deduction values for a tax procedure.</p>
    <div class="alert">

    > [!NOTE]
    > <P>After you select a line type and set up the values in the <STRONG>From</STRONG> and <STRONG>To</STRONG> fields, you can set up the additional criteria to calculate the values for the entities that correspond with the line type that you specify. The values that are returned for all of the entities that are specified for the corresponding line types are aggregated, and all of the future mathematical operations are calculated using this total.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>From</strong></p></td>
    <td><p>Select the first operand for the line type, such as a counter, pay type, rate, time code, and so on.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>To</strong></p></td>
    <td><p>Select the second operand for the line type, such as a counter, pay type, rate, time code, and so on.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Period</strong></p></td>
    <td><p>Select the duration for the calculation.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>No</strong></p></li>
    <li><p><strong>Month</strong></p></li>
    <li><p><strong>Quarter</strong></p></li>
    <li><p><strong>Half-year</strong></p></li>
    <li><p><strong>Year</strong></p></li>
    <li><p><strong>Accumulated in total</strong></p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Index</strong></p></td>
    <td><p>Enter 0 as the index for the current period, 1 as the index for the next period, and -1 as the index for the previous period.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Specification</strong></p></td>
    <td><p>Select the method that is used to calculate totals for the selected period.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Period only</strong> – Add the values for the periods that are defined in the <strong>Period</strong> and <strong>Index</strong> fields.</p></li>
    <li><p><strong>From period</strong> – Add the values for the period from the start of the period that is defined in the <strong>Period</strong> and <strong>Index</strong> fields, including the current calculation period.</p></li>
    <li><p><strong>From employment</strong> – Add the values for the period from the date of hire, including the current calculation period.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Line criteria</strong></p></td>
    <td><p>Select the condition that is applied on the current line amount to process the operation. If the condition is not met, the operator is not processed and the current counter value remains unchanged.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>=0</strong></p></li>
    <li><p><strong>&lt;&gt;0</strong></p></li>
    <li><p><strong>&lt;0</strong></p></li>
    <li><p><strong>&gt;0</strong></p></li>
    <li><p><strong>&lt;=0</strong></p></li>
    <li><p><strong>&gt;=0</strong></p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Operator</strong></p></td>
    <td><p>Select <strong>+</strong>, <strong>-</strong>, <strong>*</strong>, or <strong>/</strong> as the mathematical operator for the expression.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you do not specify an operator, the value of the current line is used as a parameter for the next line.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Sequence number</strong></p></td>
    <td><p>The sequence number of the counter line defines the order in which to run the calculation. You can modify the sequence number for the counter line.</p>
    <div class="alert">

    > [!NOTE]
    > <P>When you enter values in the <STRONG>From</STRONG> and <STRONG>Next line</STRONG> fields for the counter lines of line type <STRONG>Calculation line</STRONG> and <STRONG>Line total</STRONG>, the sequence number is used to determine the current counter line.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Next line</strong></p></td>
    <td><p>The sequence number of the next counter line to execute. If you enter a sequence number that is not available, the calculation of the counters will stop.</p></td>
    </tr>
    </tbody>
    </table>


6.  On the **General** tab, in the **Maximum** and **Minimum** fields. Enter the maximum and minimum values of the result for the line. These values define the interval of available values for the result.

7.  In the **Rounding** field, select the rounding method for the value of the counter line.

8.  In the **Precision** field, enter the precision with which to round off the value for the counter line.

9.  Repeat steps 5 through 8 to create additional counter lines.

10. Repeat steps 2 through 8 to create additional counters.

11. Click **Dependencies** to open the **Dependencies** form, where you can view the list of the dependent entities for the counter.

## 5\. Set up parameters for average earnings calculation

Use the **Average earnings calculation settings** form to set up parameters for the average earnings calculation method. You can use the average earnings calculation method to calculate salary accruals, such as per diem expenses, travel allowances, gifts, annual bonuses, vacations, and sick lists.

To set up parameters for the average earnings calculation, follow these steps:

1.  Click **Payroll (Russia)** \> **Average earnings calculation** \> **Setup** \> **General settings**.

2.  In the **From 5 to 6 days working week** field, select a rate that is used as a conversion factor to convert the working week from 5 days to 6 days.

3.  In the **From 5 to 7 days working week** field, select a rate that is used as a conversion factor to convert the working week from 5 days to 7 days.

4.  In the **Average days number in month** field, select a rate that is used to determine the number of days in the month for average earnings calculation.

5.  In the **Salary scale** field, select a rate that is used as a base salary for employees when earnings are not available for the average earnings calculation period.

6.  In the **Size of minimal wage (MROT)** field, select a rate that is used to determine the minimum monthly wage for employees.

## 6\. Set up an average earnings calculation method for all workers

Use the **Average earnings calculation method** form to set up the calculation methods for all of the workers in a legal entity.

To set up an average earnings calculation method for all workers, follow these steps:

1.  Click **Payroll (Russia)** \> **Average earnings calculation** \> **Setup** \> **Calculation method**.

2.  Click **New** or press CTRL+N to create an average earnings calculation method for all of the workers.

3.  In the **Calculation method code** and **Name** fields, enter an identification code and a name for the calculation method.

4.  In the **Number of month** field, select the identification code for a rate that contains the number of months for the average earnings calculation period.

5.  In the **Working week duration** field, select **5 days**, **6 days**, or **7 days** as the duration of the work week.

6.  In the **Calculation method of short month** field, select the calculation method for the days or hours that are worked, and apply it to each month within the average earnings calculation period during which the employee did not work for the full month.
    
    Select from the following options:
    
      - **Summary** – The number of days or hours that are worked is calculated using resulting information about the employee days or hours that are worked for the month:The days or hours that are available to work according to the schedule - The days or hours that the employee is absent.
    
      - **Calendar** – The number of days or hours that are worked is calculated using the daily timesheet and calendar details:
        
        ((The days or hours according to the schedule - The days or hours that the employee is absent) / The number of calendar days in the month) \* The average number of days in the month.
    
      - **By coefficient** – The number of days or hours that are worked is calculated using the resulting information from the number of employee days or hours that are worked for the month, the actual time that is worked considering the conversion factor that is set for the calendar of the employee, and the working week duration.

7.  In the **Calculation type** field, select **By days** or **By hours** to calculate average daily or hourly earnings.
    

    > [!NOTE]
    > <P>If you select <STRONG>Calendar</STRONG> in the <STRONG>Calculation method of short month</STRONG> field, you must select <STRONG>By days</STRONG> In this field.</P>



8.  On the **General** tab, specify numerical parameters, time parameters, and bonus parameters for the calculation method.
    
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
    <td><p><strong>Calculation method of full month</strong></p></td>
    <td><p>Select the average earnings calculation method for the days or hours that are worked, and apply it to each month within the average earnings calculation period that the employee worked for the entire month.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>According to calendar</strong> – The number of days or hours that are worked in the calculation period according to the working schedule.</p></li>
    <li><p><strong>Average value</strong> – The average number of days or hours in a month.</p></li>
    </ul></td>
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
    > <P>The average earnings base is applied for the average earnings calculation instead of the <STRONG>Base of calculation</STRONG> when there are no accruals available for previous calculation periods that are included in the base of calculation.</P>


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


## 7\. Set up an average earnings calculation method for a single worker

Use the **Employee average earnings calculation method** form to set up an average earnings calculation method for a single worker. This calculation method is used for a worker instead of the method that has the same identification code that is configured for all workers.

To set up an average earnings calculation method for a single worker, follow these steps:

1.  Click **Payroll (Russia)** \> **Average earnings calculation** \> **Setup** \> **Employee setup**.

2.  Click **New** or press CTRL+N to create an average earnings calculation method for a worker.

3.  In the **Calculation method code** field, select the identification code for the calculation method that you created for all workers. The name of the calculation method is updated in the **Name** field.
    

    > [!NOTE]
    > <P>The details of the selected calculation method are updated in the corresponding fields on the <STRONG>Overview</STRONG> and <STRONG>General</STRONG> tabs.</P>



4.  In the **Employee** field, select the identification code of the employee to set up the calculation method for. Make sure that you select an employee for whom you have defined a working schedule. The name of the employee is updated in the **Employee name** field.

5.  All the fields are updated with the values for the selected average earnings calculation method that you set up. You can modify the values in the fields, if required. For more information, see 6. Set up an average earnings calculation method for all workers.

## Next step

You have finished setting up the calculation procedures for the payroll process. Continue to set up additional parameters for the payroll process. For more information, see the following topics:

  - [(RUS) Set up parameters for the payroll process](rus-set-up-parameters-for-the-payroll-process.md)

  - [(RUS) Set up payments, journals, and deductions for the payroll process](rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md)

  - [(RUS) Set up vacations, business trips, and incentives for the payroll process](rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md)

  - [(RUS) Set up taxes and funds for the payroll process](rus-set-up-taxes-and-funds-for-the-payroll-process.md)

After you complete all of the setup tasks for the payroll process, continue to calculate payments for workers. For more information, see the following topics:

  - [(RUS) Create and post a vacation resolution](rus-create-and-post-a-vacation-resolution.md)

  - [(RUS) Create and post a business trip resolution](rus-create-and-post-a-business-trip-resolution.md)

  - (RUS) Register vacations, business trips, and calculate compensation

  - [(RUS) Create and post an incentive resolution](rus-create-and-post-an-incentive-resolution.md)

  - (RUS) Configure standard deductions calculation

  - [(RUS) Generate pay statements](rus-generate-pay-statements.md)

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
<td><p>To set up calculation procedures for the payroll process, you must be a member of a security role that includes the following duties.</p>
<ul>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
<li><p><strong>Enable human resource process</strong> (HcmHREnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitProcessInquire)</p></li>
<li><p><strong>Inquire into human resources process</strong> (RPayHumanResourcesProcessInquire)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up calculation procedures for the payroll process, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p><strong>Maintain average earnings calculation methods</strong> (RPayAECalMethodMaintain)</p></li>
<li><p><strong>Maintain average earnings calculation parameters</strong> (RPayAECalcParametersMaintain)</p></li>
<li><p><strong>View average earnings calculation methods</strong> (RPayAECalcMethodsView)</p></li>
<li><p><strong>View average earnings calculation parameters</strong> (RPayAECalcParamsView)</p></li>
<li><p><strong>View calculation procedures</strong> (RPayCalcProcView)</p></li>
<li><p><strong>View groups of calculation procedures</strong> (RPayCalcProcGroupView)</p></li>
<li><p><strong>Maintain calculation procedures</strong> (RPayCaclProcMaintain)</p></li>
<li><p><strong>Maintain calculation sequences</strong> (RPayCalcSeqMaintain)</p></li>
<li><p><strong>Maintain groups of calculation procedures</strong> (RPayProcGroupMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


