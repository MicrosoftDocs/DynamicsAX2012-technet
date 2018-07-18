---
title: (RUS) Set up vacations, business trips, and incentives for the payroll process
TOCTitle: (RUS) Set up vacations, business trips, and incentives for the payroll process
ms:assetid: 9469075a-52ae-42dc-bfd0-a31388d2fa55
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn435989(v=AX.60)
ms:contentKeyID: 56732189
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- bonus
- business
- vacation
- incentive
- average earnings
- calculation method
- Forms.RPayAverageEarnEmplTable
- average earning
- bonus type
- bonus types
- bonuses
- business trip
- business trips
- Forms.RHRMBonusCode
- Forms.RHRMBusinessTripType
- Forms.RHRMVacationType
- Forms.RPayBusinessTripParameters
- Forms.RPayVacationParameters
- incentives
- trip
- trip type
- trip types
- trips
- vacation type
- vacation types
- vacations
- MsDynAx060.Forms.RPayAverageEarnEmplTable
- MsDynAx060.Forms.RHRMBonusCode
- MsDynAx060.Forms.RHRMBusinessTripType
- MsDynAx060.Forms.RPayVacationParameters
- MsDynAx060.Forms.RPayBusinessTripParameters
- MsDynAx060.Forms.RHRMVacationType
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up vacations, business trips, and incentives for the payroll process 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to set up vacation types, business trip types, and bonus types, as well as how to set up calculation methods for vacations and business trips.

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
<li><p>Create a list of time codes for working time, overtime, idle time, vacation, sick leave, and business trips. For more information, see <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
<li><p>Set up parameters for payroll calculation, payroll groups, rates and dependencies for payroll calculation, payroll posting profiles, pay types, and funds. For more information, see <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></li>
<li><p>Set up calculation procedures, their sequences and counters, and calculation methods to calculate the salaries for workers. For more information, see <a href="rus-set-up-calculation-procedures-for-the-payroll-process.md">(RUS) Set up calculation procedures for the payroll process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up types of vacations

Use the **Vacation types** form to set up codes for the types of vacation that are taken by an employee, and enter details for the vacation calculations.

To set up types of vacations, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Vacation types**.

2.  Press CTRL+N to create a vacation type record.

3.  In the **Type of vacation** and **Description** fields, enter a code and a description for the vacation type.

4.  In the **Vacation type** field, select **Basic** or **Additional/optional** as the type of vacation. In the **Time code** field, select a time code for the vacation. The information that is related to this time code is updated in the timesheet when you register a vacation of this type.

5.  In the **Calculation method code** field, select the code for the average earning calculation method.

6.  On the **General** tab, select the **Unpaid vacation** check box to transfer the information about vacation without pay to the Pension fund.

7.  In the **Insurance seniority type** field, select the identification code of the insurance seniority type for the vacation type. The information that is related to this code is transferred to the Pension fund.

8.  In the **Vacation payment calculation** field group, specify values in the following fields:
    
    1.  In the **Sequence** field, select the sequence code for the vacation payment calculation.
    
    2.  In the **Duration** field, select the rate to determine the duration of the vacation days that are granted for one month of employee seniority in the legal entity.
    
    3.  Select the **Ignore in seniority calculation** check box to exclude vacations of this type from the calculation of seniority that is used to calculate the number of earned vacation days.

9.  In the **Calculation of compensation** field group, specify the values in the following fields:
    
    1.  Select the **Calculation of compensation** check box to compensate the earned vacation days for this vacation type. This is used to calculate the vacation compensation payment at dismissal.
    
    2.  In the **Sequence** field, select the sequence code for vacation compensation calculation.

10. Select the **Including holiday days** check box to include non-working holiday days of vacation in the number of payable calendar days of vacation.

## 2\. Set up a vacation calculation method for all workers

Use the **Vacation calculation settings** form to set up the vacation calculation method that is used to calculate vacation payments for all of the workers. Microsoft Dynamics AX uses the time group that you specify in this form to calculate the days or hours worked using the average earnings calculation base and the selected vacation calculation method.

To set up a vacation calculation method for all workers, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Vacations** \> **Setup** \> **General settings**.

2.  Click **New** or press CTRL+N to create a vacation calculation method.

3.  In the **Calculation method code** and **Name** fields, enter an identification code and a name for the calculation method.

4.  In the **Number of month** field, select the identification code for a rate that contains the number of months for the average earnings calculation period to use in the vacation payment calculation.

5.  In the **Working week duration** field, select **5 days**, **6 days**, or **7 days** as the duration of the work week.

6.  In the **Calculation method of short month** field, select the calculation method for the days or hours that are worked and apply it to each month within the average earnings calculation period during which the employee did not work for the full month.
    
    Select from the following options:
    
      - **Summary** – The number of days or hours that are worked is calculated using resulting information about the employee days or hours that are worked for the month:
        
        The days or hours that are available to work according to the schedule - The days or hours that the employee is absent.
    
      - **Calendar** – The number of days or hours that are worked is calculated using the daily timesheet and calendar details:
        
        ((The days or hours according to the schedule - The days or hours that the employee is absent) / The number of calendar days in the month) \* The average number of days in the month.
    
      - **By coefficient** – The number of days or hours that are worked is calculated using the resulting information from the number of employee days or hours that are worked for the month, the actual time that is worked considering the conversion factor that is set for the calendar of the employee, and the working week duration.

7.  In the **Calculation type** field, select **By days** or **By hours** to calculate the average daily or hourly earnings.
    

    > [!NOTE]
    > <P>If you select <STRONG>Calendar</STRONG> in the <STRONG>Calculation method of short month</STRONG> field, you must select <STRONG>By days</STRONG> in this field.</P>



8.  On the **Average earnings** tab, specify time parameters, numerical parameters, and bonus parameters for the calculation method.
    
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
    <li><p><strong>According to calendar</strong> – The number of days or hours in the calculation period according to the working schedule.</p></li>
    <li><p><strong>Average value</strong> – The average number of days or hours per month.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Duration</strong></p></td>
    <td><p>Select <strong>5 days</strong>, <strong>6 days</strong>, or <strong>7 days</strong> as the duration of the work week.</p></td>
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
    <td><p><strong>Base of calculation</strong></p></td>
    <td><p>Select the identification code for the average earnings calculation base. The base includes pay types that are used in the average earnings calculation.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Average earnings base</strong></p></td>
    <td><p>Select the identification code for the average earnings calculation base. The base includes pay types that are used in the average earnings calculation.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The average earnings base is applied for the average earnings calculation instead of base of calculation when there are no accruals available for previous calculation periods that are included in the base of calculation.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Step-up ratio</strong></p></td>
    <td><p>Select the rate that contains the ratio to index the average earnings during the calculation period.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Bonus base</strong></p></td>
    <td><p>Select a calculation base that includes pay types that correspond with awards that are made for the period from the material incentives fund.</p></td>
    </tr>
    <tr class="odd">
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
    <tr class="even">
    <td><p><strong>Proportional calculation</strong></p></td>
    <td><p>Select this check box to indicate that bonuses are included in the average earnings calculation in proportion to the days or hours worked.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Non decreased number of days</strong></p></td>
    <td><p>Select the rate that is used to determine the number of days on vacation per year that are not excluded from the length of service.</p></td>
    </tr>
    </tbody>
    </table>


9.  On the **General** tab, in the **Sequence for additional payment calculation** field, select the sequence of additional payment calculation that you set up for the vacation. The sequence is started after the basic vacation calculation.

10. In the **Work week duration** field, enter the work week duration in hours.

## 3\. Set up a vacation calculation method for a single worker

Use the **Employee average earnings calculation method** form to create or modify a vacation calculation method for a single worker. This calculation method is used for a worker instead of the method that has the same identification code that is configured for all workers.

To set up a vacation calculation method for a single worker, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Vacations** \> **Setup** \> **Employee setup**.

2.  Click **New** or press CTRL+N to create an average earnings calculation method for a worker.

3.  In the **Calculation method code** field, select the identification code for the calculation method that you created for all workers.
    

    > [!NOTE]
    > <P>The details of the selected calculation method are updated in the corresponding fields on the <STRONG>Overview</STRONG> and <STRONG>General</STRONG> tabs.</P>



4.  In the **Employee** field, select the identification code of the employee to set up the calculation method for. Make sure that you select an employee for whom you have defined a working schedule. The name of the employee is updated in the **Employee name** field.

5.  All of the fields are updated with the values for the selected average earnings calculation method that you set up. You can modify the values in the fields, if required. For more information, see 2. Set up a vacation calculation method for all workers.

## 4\. Set up types of business trips

Use the **Business trip types** form to set up codes for the types of business trips that are taken by an employee, and enter details for the calculation of business trips.

To set up types of business trips, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Business trip types**.

2.  In the **Business trip type** and **Description** fields, enter an identification code and a description for the business trip type.

3.  In the **Time code** field, select a time code for the business trip. The selected business trip is displayed with this time code in the working time registration table.

4.  In the **Sequence** field, select a sequence for the business trip calculation.

5.  In the **Calculation method code** field, select the identification code for the business trip calculation method.

## 5\. Set up a business trip calculation method

Use the **Business trip calculation settings** form to set up a business trip payment calculation method that is used to calculate business trip payments for all of the workers.

To set up a business trip calculation method for all workers, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Business trips** \> **Setup** \> **General settings**.

2.  Click **New** of press CTRL+N to create a business trip calculation method.

3.  In the **Calculation method code** and **Name** fields, enter an identification code and a name for the calculation method.

4.  In the **Number of month** field, select the identification code for a rate that contains the number of months for the average earnings calculation period to use in the business trip payment calculation.

5.  In the **Working week duration** field, select **5 days**, **6 days**, or **7 days** as the duration of the work week.

6.  In the **Calculation method of short month** field, select the calculation method for the days or hours that are worked and apply it to each month within the average earnings calculation period during which the employee did not work for the full month.
    
    Select from the following options:
    
      - **Summary** – The number of days or hours that are worked is calculated using resulting information about the employee days or hours that are worked for the month:
        
        The days or hours that are available to work according to the schedule - The days or hours that the employee is absent.
    
      - **Calendar** – The number of days or hours that are worked is calculated using the daily timesheet and calendar details:
        
        ((The days or hours according to the schedule - The days or hours that the employee is absent) / The number of calendar days in the month) \* The average number of days in the month.
    
      - **By coefficient** – The number of days or hours that are worked is calculated using the resulting information from the number of employee days or hours that are worked for the month, the actual time that is worked considering the conversion factor that is set for the calendar of the employee, and the working week duration.

7.  In the **Calculation type** field, select **By days** or **By hours** to calculate average daily or hourly earnings.
    

    > [!NOTE]
    > <P>If you select <STRONG>Calendar</STRONG> in the <STRONG>Calculation method of short month</STRONG> field, you must select <STRONG>By days</STRONG> in this field.</P>



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
    <li><p><strong>According to calendar</strong> – The number of days or hours in the calculation period according to the working schedule.</p></li>
    <li><p><strong>Average value</strong> – The average number of days or hours per month.</p></li>
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


## 6\. Set up a business trip calculation method for a single worker

Use the **Employee average earnings calculation method** form to create or modify a business trip calculation method for a single employee.

To set up a business trip calculation method for a single worker, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Business trips** \> **Setup** \> **Employee setup**.

2.  Click **New** or press CTRL+N to create an average earnings calculation method for a worker.

3.  In the **Calculation method code** field, select the identification code for the calculation method that you created for all workers.
    

    > [!NOTE]
    > <P>The details of the selected calculation method are updated in the corresponding fields on the <STRONG>Overview</STRONG> and <STRONG>General</STRONG> tabs.</P>



4.  In the **Employee** field, select the identification code of the employee to set up the calculation method for. Make sure that you select an employee for whom you have defined a working schedule. The name of the employee is updated in the **Employee name** field.

5.  All of the fields are updated with the values for the selected average earnings calculation method that you set up. You can modify the values in the fields, if required. For more information, see 5. Set up a business trip calculation method.

## 7\. Set up types of bonuses

Use the **Bonus types** form to set up codes for incentives that are offered to employees within your legal entity.

To set up types of bonuses, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Bonus types**.

2.  Click **New** of press CTRL+N to create a bonus type.

3.  In the **Bonus code** field, enter an identification code for the bonus type.

4.  In the **Bonus type** field, enter a description of the bonus type.

5.  In the **Pay type** field, select the pay type to apply to this bonus type when the incentive resolutions with this bonus type are used to automatically generate payroll journal lines. For more information about how to create a payroll journal, see “1. Create and post a payroll journal” in [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## Next step

You have finished setting up vacations, business trips, and incentives. Continue to set up additional parameters for the payroll process. For more information, see the following topics:

  - [(RUS) Set up payments, journals, and deductions for the payroll process](rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md)

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
<td><p>To set up vacations, business trips, and incentives for the payroll process, you must be a member of a security role that includes the following duties.</p>
<ul>
<li><p><strong>Enable human resource process</strong> (HcmHREnable)</p></li>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Inquire into human resources process</strong> (RPayHumanResourcesProcessInquire)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitProcessInquire)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up vacations, business trips, and incentives for the payroll process, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p><strong>Maintain bonus types</strong> (RPayBonusTypesMaintain)</p></li>
<li><p><strong>Maintain business trip parameters</strong> (RPayBTParamMaintain)</p></li>
<li><p><strong>Maintain business trip types</strong> (RPayBTTypesMaintain)</p></li>
<li><p><strong>Maintain business trips resolution</strong> (RPayBTResolutionMaintain)</p></li>
<li><p><strong>Maintain employment terms</strong> (HcmEmploymentTermMaintain)</p></li>
<li><p><strong>Maintain vacation parameters</strong> (RPayVacParamMaintain)</p></li>
<li><p><strong>Maintain vacation types</strong> (RPayVacTypesMaintain)</p></li>
<li><p><strong>Maintain vacations resolution</strong> (RPayVacResolutionMaintain)</p></li>
<li><p><strong>View bonus types</strong> (RPayBonusesView)</p></li>
<li><p><strong>View business trip parameters</strong> (RPayBTParamView)</p></li>
<li><p><strong>View business trip types</strong> (RPayBTTypesView)</p></li>
<li><p><strong>View vacation parameters</strong> (RPayVacParamsView)</p></li>
<li><p><strong>View vacation types</strong> (RPayVacTypesView)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


