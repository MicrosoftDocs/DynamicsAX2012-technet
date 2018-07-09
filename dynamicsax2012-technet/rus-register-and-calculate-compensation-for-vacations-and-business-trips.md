---
title: (RUS) Register and calculate compensation for vacations and business trips
TOCTitle: (RUS) Register and calculate compensation for vacations and business trips
ms:assetid: c530ebaf-bab5-4c91-9a63-aacebf7de1aa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn781410(v=AX.60)
ms:contentKeyID: 62807375
ms.date: 08/20/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RPayEmplCalculate
- MsDynAx060.Forms.RPayEmplCalculate
- Forms.RPayBusinessTripTable
- Forms.RPayVacationTable
- MsDynAx060.Forms.RPayBusinessTripTable
- MsDynAx060.Forms.RPayVacationTable
---

# (RUS) Register and calculate compensation for vacations and business trips [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to complete the following tasks:

  - Register vacations

  - Calculate vacation payments and compensation

  - Register business trips

  - Calculate average earnings for business trips

  - Enter trip time on timesheets

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
<td><p>Setup tasks</p></td>
<td><ul>
<li><p>Set up time codes for vacations in the <strong>Timesheet general settings</strong> form.</p></li>
<li><p>Set up calendars for employees in the <strong>Calendar</strong> form.</p></li>
<li><p>Set up calculation sequences for vacation payments, business trip payment calculations, and compensation in the <strong>Sequence of calculation</strong> form.</p></li>
<li><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Calculation procedures</strong> &gt; <strong>Vacations</strong> &gt; <strong>Vacation registration</strong>. Set the timesheet update toggle button to the <strong>Timesheet update - Yes</strong> mode to update the timesheet before you register a vacation.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Vacations</p></td>
<td><p></p>
<ul>
<li><p>Set up vacation type codes in the <strong>Vacation types</strong> form.</p></li>
<li><p>Enter the calculation method of vacation average earnings for all employees in the <strong>Vacation calculation settings</strong> form.</p></li>
<li><p>Enter the calculation method of vacation average earnings for a specific employee in the <strong>Employee average earnings calculation method</strong> form, if required.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Business trips</p></td>
<td><ul>
<li><p>Set up business trip type codes in the <strong>Business trip types</strong> form.</p></li>
<li><p>Enter the business trip calculation method for all employees in the <strong>Business trip calculation settings</strong> form.</p></li>
<li><p>Enter the business trip calculation method for a specific employee in the <strong>Employee average earnings calculation method</strong> form, if required.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Register vacations and calculate vacation compensations

Use the **Vacations** form to register vacations manually. You can also register vacation details by using posted vacation resolutions from the **Vacation resolution** form. You can enter the vacation time in the timesheet manually, or the timesheet is updated automatically if **Timesheet update - Yes** is selected in the **Vacations** form.

Vacation compensation is calculated based on the average earnings of an employee. When the vacation compensation is calculated, the vacation payment is divided across payment periods. After you add the vacation line to the payroll, it is processed at the start of the vacation payment calculation.

Vacation compensation details about the dismissed employee are updated automatically when you post a dismissal resolution in the **Dismissal resolutions** form. After you modify the vacation details for an employee, you can recalculate their vacation compensation in the **Recent transactions** form.

## Register vacations for an employee

To register vacations for an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Vacations** \> **Vacation registration**.

2.  In the **Type of vacation** field, select the code for the type of vacation.

3.  In the **Calculation method code** field, select the average earnings method identification code (ID) for the vacation calculation. If necessary, you can modify this value.

4.  Use the information in the following table to select the type of vacation.
    
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
    <td><p><strong>Type</strong></p></td>
    <td><p>Select the type of the vacation from the following options.</p>
    <ul>
    <li><p><strong>Vacation</strong> – The payment amount for the granted vacation is calculated.</p>
    <p>To extend a vacation, create a new line, and then in the <strong>Associated vacation</strong> field, select the starting date of the original vacation. The vacation type and average-earned wages are taken from the extended vacation. You cannot recalculate them. The start date of the vacation extension displays by default. This value indicates the day that follows the end date of the prolonged vacation.</p></li>
    <li><p><strong>Vacation breaking</strong> – The deduction of the granted vacation payment for the period of the vacation interruption is calculated.</p>
    <p>To interrupt a vacation, create a new line, select the <strong>Vacation breaking</strong> line type, and then in the <strong>Associated vacation</strong> field, select the starting date of the original vacation. The vacation type and the average-earned wages are taken from the interrupted vacation. You cannot recalculate them.</p></li>
    <li><p><strong>Compensation</strong> – The compensation payment for the unused vacation is calculated. Compensation for unused vacation can be calculated automatically or manually when you post a dismissal resolution. When you calculate compensation manually, the number of days for which the vacation is granted is calculated automatically from the starting date.</p>
    <p>You can modify this value in the <strong>Quantity of days</strong> field. The compensation is usually paid for an employee's dismissal date. It is not considered to be time spent by an employee on vacation.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


5.  In the **Employee** field, select the ID of the employee to whom the vacation is granted based on the average wages that are earned.

6.  In the **Start date** field, select the starting date of the granted vacation.
    

    > [!NOTE]
    > <P>The starting date of the original vacation for the calculation of the interrupted or prolonged vacation is displayed in the <STRONG>Associated vacation</STRONG> field.</P>



7.  In the **Quantity of days** field, enter the number of payable vacation days that are granted. The ending date is estimated automatically based on the vacation type and calendar setup.

8.  In the **End date** field, select the ending date of the granted vacation. The quantity of payable days is estimated automatically based on the vacation type and calendar setup. Click the **Calculation** tab to calculate the registered vacation line.

9.  Select the **Add to salary** check box to add the vacation payment amount to the payments and deductions for the employee. If the vacation payment amount is added to the salary, the current payroll period is automatically displayed in the **Calculation period** field.

10. When the payroll is calculated, in the **Amount to be paid** field, the vacation pay is also updated. You can manually adjust the vacation pay details if you want to pay a part of the accrued vacation. This amount includes the value of the vacation pay that is to be used in the vacation pay-sheet line. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md) and (RUS) Issue payments to workers.

## If required: Register vacations from a vacation resolution

You can use the vacation payment details from the **Vacation resolution** form to register vacations in the **Vacations** form. The Payroll accountant uses the information that is prepared by the Human Resources (HR) department. You don’t have to create a vacation resolution if you are in the Payroll department.

To register vacations from a vacation resolution, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Vacations** \> **Vacation registration**.

2.  Click **Enter from order** to open the **Creating vacation lines on the basis of vacation orders** form.
    
    You can view the registered vacation resolution details from the **Vacation resolution** form. For more information, see [(RUS) Create and post a vacation resolution](rus-create-and-post-a-vacation-resolution.md). You can click **From orders** or **From order's lines** to register vacations based on the selected order or lines. You can also calculate the order or order lines, and include them in the payroll.

## If required: Modify and calculate the vacation payment details

To modify and calculate the vacation payment details, follow these steps:

1.  In the **Vacations** form, on the **General** tab, you can modify the average-earnings calculation method details to calculate vacation payments for a specified employee. For example, if the timesheet is defined in hours for the employee, select **By hours** in the **Calculation type** field.

2.  If you want to modify the vacation payment amount and source details for the average earnings calculation for the employee, you can modify the field values on the **Calculation** tab.
    
    In the **Salary Report** field group, the average earnings calculation details are displayed with the payment source and the calculation period. In the **Benefit due** field group, the vacation payment amount and payment period are displayed. You can modify these fields only if the vacation is not included in the salary calculation. Based on the values in the **Salary Report** field group, the values in the **Benefit due** field group are recalculated.
    
    To recalculate and view, follow these steps:
    
    1.  Click **Recalculation** to recalculate the amounts that are due to the employees for the vacation time.
    
    2.  Click **Payroll lines** to view the payroll transactions from the wage fund that are used to calculate the average earnings of the vacation.
    
    3.  Click **Bonuses** to view the payroll transactions from the incentive fund that are used to calculate the average earnings of the vacation.
        
        When the vacation record is included in the salary of the current payroll period, all amounts from the **Benefit due** field group that are registered for any payment period are used to generate payroll transactions.

3.  Click **Calculation** to define the criteria for the vacation payment calculation in the **Vacation payment calculation** form, and calculate the payroll for this employee.

4.  Click **OK** to close the **Vacation payment calculation** form. You can view the final amount to be paid as vacation compensation in the **Vacations** form.
    

    > [!NOTE]
    > <P>The final vacation compensation amount can be changed after the next recalculation as long as it is marked as locked, or is included in vacation pay-sheets.</P>



5.  To view the work hour details for the employee during the selected calculation period, in the **Resulting information about employee worked hours** form, click **Hours worked accounting**.

## If required: Recalculate modified vacation details and print the T-60 report

To recalculate modified vacation details for employees in the **Recent transactions** form, follow these steps:

1.  Click **Payroll (Russia)** \> **Payroll calculation** \> **Recent transactions**.

2.  Click **New** to create a transaction.

3.  In the **Employee** field, select the employee code.

4.  In the **Procedure code** field, select the calculation procedure code for the vacation.

5.  Click **Recalculate current** to recalculate the vacation compensation for the selected employee.
    
    –or–
    
    Click **Recalculate all** to recalculate the vacation compensation for all employees.

6.  Click **Adjust storno** to process the storno adjustment for the selected vacation that was already included in the payroll within the closed period. Click **View the storno** to view the storno adjustment details for the original document.

To print the statutory report, which explains the vacation calculation details, follow these steps:

1.  To print the required statutory report T-60, click **Print** to open the **Report options** form.

2.  Enter the necessary details, and then click **OK** to print the T-60 report.

## 2\. Register business trips and calculate business trip compensation

You can use the **Business trips** form to register a business trip and calculate compensation for the business trip. Depending on the business trip type, the timesheets can be generated in the following ways:

  - **Business trip** – The timesheets are generated in the same manner as vacations and sick lists.

  - **Business trip breaking** – The timesheets are updated if you are using the daily assessment principle and the employee returns to work before the granted business trip is over. If you are using the summary assessment principle, the days or hours that are worked during the business trip break period are subtracted from the total number of days or hours that are planned for business trips of the same type. If vacations or sick lists fall within the break period, their days or hours are added to the timesheet.

Employees’ timesheets are updated with a time code that is specified in the **Time code** field for the selected **Business trip** option in the **Timesheet general settings** form. For more information, see [(RUS) Configure parameters for time management](rus-configure-parameters-for-time-management.md).

Average earnings for a business trip are calculated according to the calculation method that is configured for business trip payments. Business trip payments are calculated and registered as payroll transactions according to the counter setup rules for business trip payments.

## Register business trips for an employee

To register business trips, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Business trips** \> **Business trip registration**.

2.  In the **Business trip type** field, select the ID for the business trip type.

3.  In the **Calculation method code** field, the average earnings method ID for the business trip calculation is displayed. If necessary, you can modify this value.
    
    Use the following table to select the type of business trip to determine whether payment is allowed for the selected business trip.
    
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
    <td><p><strong>Type</strong></p></td>
    <td><p>Select the type of the business trip from the following options.</p>
    <ul>
    <li><p><strong>Business trip</strong> – The business trip payment amount is calculated for the standard business trip or for the business trip extension.</p></li>
    <li><p><strong>Business trip breaking</strong> – The business trip payment amount is calculated for the interrupted business trip.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


4.  In the **Employee** field, select the ID of the employee that the business trip is registered for.

5.  In the **Start date** field, select the starting date of the business trip.
    

    > [!NOTE]
    > <P>If you select a business trip that has <STRONG>Business trip</STRONG> as its type and a related business trip date is selected, the start date is automatically updated with the date that falls one day after the end date of the related business trip. You can modify the date. If you select a business trip that has <STRONG>Business trip breaking</STRONG> as its type, the starting date of the business trip must be within the related business trip period.</P>



6.  In the **Quantity of days** field, enter the number of days that the business trip is calculated for.

7.  In the **End date** field, select the ending date of the business trip.

8.  Select the **Add to salary** check box to add the business trip payment amount to the payments and deductions for the employee. If the business trip payment amount is added to the salary, the month and year of the current period automatically display in the **Calculation period** field.

## If required: Register business trips from a business trip resolution

You can use the calculated business trip resolution details from the **Business trip resolutions** form to register business trips. The Payroll accountant uses the information that is prepared by the HR department. You don’t have to create a business trip resolution if you are a member of the Payroll department.

To register business trips, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Business trips** \> **Business trip registration**.

2.  Click **Enter from order** to open the **Creating business trip lines on the basis of business trip orders** form.
    
    You can view the business trip resolution details in the **Business trip resolutions** form. You can also click **From orders** or **From order's lines** to register a business trip based on the selected order or lines. You can calculate the order or order lines, and include them in the payroll. For more information, see [(RUS) Create and post a business trip resolution](rus-create-and-post-a-business-trip-resolution.md).

## If required: Modify and calculate business trip compensation

To modify and calculate the business trip compensation details, follow these steps:

1.  In the **Business trips** form, on the **General** tab, modify the calculation method details to calculate business trip payments and time parameters for a specified employee.

2.  If you want to modify the business trip payment amount and source details for the average earnings calculation for the employee, modify the field values on the **Calculation** tab.
    
    In the **Salary Report** field group, the average earnings calculation details are displayed with the payment source and the calculation period. In the **Benefit due** field group, the business trip payment amount and the payment period are displayed. You can modify these fields only if the vacation is not included in the salary calculation. Based on the values in the **Salary Report** field group, the values in the **Benefit due** field group are recalculated.
    
    To calculate and view, follow these steps:
    
    1.  Click **Recalculation** to recalculate the vacation due amounts.
    
    2.  Click **Payroll lines** to view the payroll transaction amounts from the wage fund that are used to calculate the average earnings of the business trip.
    
    3.  Click **Bonuses** to view the payroll transactions from the incentive fund that are used to calculate the average earnings of the business trip.
        
        When the business trip record is included in the salary from the current payroll period, only the amounts from the **Benefit due** field group that are registered for a payment period, and which are equal to the current payroll period, are used to generate the payroll transaction. Other details from the **Benefit due** field group are used to generate payroll transactions, as the current payroll period matches the payment period.

3.  You can click **Calculation** to define the criteria for the business trip payment calculation in the **Business trip calculation** form and calculate the payroll for this employee.

4.  Click **OK** to close the **Business trip calculation** form. You can view the final amount to be paid as business trip compensation in the **Business trips** form.

5.  Click **Hours worked accounting** to view the working hour details for the employee during the selected calculation period in the **Resulting information about employee worked hours** form.

6.  Click **Adjust storno** to process the storno adjustment for the selected business trip type that was already included in the payroll within the closed period. Click **View the storno** to view the storno adjustment details for the original document.

## Next step

You have registered vacations and business trips. Continue to register related payments, and then continue to manage pay statements. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## Related tasks

RUS) Register sick lists manually and calculate compensation

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
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must have the following role:</p>
<ul>
<li><p>Payroll Assistant</p></li>
<li><p>Payroll Assistant</p></li>
<li><p>Compensation and Benefits Manager</p></li>
<li><p>Payroll Manager</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Security privileges</p></td>
<td><p>To configure vacations and business trips, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Maintain average earnings calculation</strong></p></td>
<td><p>RpayAverageBonusSum</p>
<p>RPayAverageEarnEmplPeriodTable</p>
<p>RPayCalendarTable</p>
<p>RPayReverse</p></td>
<td><p><strong>Register vacations manually and calculate vacation compensation</strong></p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

