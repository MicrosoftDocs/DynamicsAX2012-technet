---
title: (RUS) Set up employee compensation parameters
TOCTitle: (RUS) Set up employee compensation parameters
ms:assetid: 3a85457c-2d46-4b02-8d76-f08704aaa65a
ms:mtpsurl: https://technet.microsoft.com/library/Dn502638(v=AX.60)
ms:contentKeyID: 59361493
author: Khairunj
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.Dialog
- civil contract
- civil code
- compensation
- contract types
- employee compensation
- Forms.RHRMGradeScaleLine
- Forms.RHRMGradeScaleTable
- Forms.RPaySickListParameters
- incapacities
- injuries
- labor agreement
- labor code
- labor contract
- pay frequencies
- pay frequency
- scale of charges
- sick lists
- types of work incapacities
- types of work incapacity
- wage grades
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up employee compensation parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes about how to set up types of incapacities and injuries, the scale of charges, and pay frequencies for employee compensation payments.

The work compensation parameters are necessary to determine the payment that an employee receives when the employee performs their duties. The level of compensation can be defined by scale of charges while the pay frequency defines the frequency of making payments.

The work incapacity compensation parameters are necessary to determine the amount of pay that an employee receives when the employee is unable to work because of certain types of incapacities that are covered by social insurance fund and the wage fund. When employees are absent, they receive social insurance payments.

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
<th><p>Prerequisites</p></th>
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
<td><ul>
<li><p>Set up employee categories. For more information, see <a href="rus-configure-staff-administration-information-for-workers.md">(RUS) Configure staff administration information for workers</a>.</p></li>
<li><p>Set up the time management settings. For more information, see <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up types of work incapacities and injuries

You can set up certain work incapacities to refer to if an employee is temporarily unable to work. You can use the **Sick lists** form to register a sick list that defines the temporary work incapacity. An employee may temporarily be unable to work because of various incapacities related to child care, illness of the employee, illness of dependents, or occupational diseases. In these cases, the company makes contributions to the social insurance fund on behalf of the employee. These contributions or insurance fees are used by the employee when the employee is unable to work.

An employee can also be absent because of child rearing leave. An employee cannot be compensated for more than 100 percent of the average earnings per month for this incapacity. Employees who work in unfavorable conditions are compensated by the government for a longer duration with more compensation and increased minimum average earnings than regular employees. Also, the employees must have a minimum average earning that is defined by the government.

To set up the types of work incapacities, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Sick lists** \> **Setup** \> **General settings**.

2.  On the **General** tab, select details for compensation calculations.
    
    Use the information in the following table to select the compensation parameters.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Fields</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Length of service</strong></p></td>
    <td><p>Select the seniority that corresponds to the duration for which the employee is insured and for which the employer pays contribution to the social fund. This seniority is used to calculate social allowance.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Period of restriction calculation</strong></p></td>
    <td><p>Select the number of months that precede the incapacity start date that is used to collect information for average earnings calculation.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>From 5 to 7 days working week</strong></p></td>
    <td><p>Select the conversion factor to convert a 5-day working week to a 7-day week.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Excluded time group</strong></p></td>
    <td><p>Select the time group that contains the time codes that is to calculate the number of days that are excluded from the number of calendar days.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The excluded number of days is used to calculate the daily average earnings. The daily average earnings are used to calculate social fund contributions for specific kinds of incapacities related to child care.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Group code</strong></p></td>
    <td><p>Select the time group that contains the time codes that calculates the part time coefficient that is applied when the incapacity compensation allowance is paid from MROT.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calendar</strong></p></td>
    <td><p>Select the calendar that is used to calculate the part time coefficient when the allowance is paid based on MROT.</p>
    <div class="alert">

    > [!NOTE]
    > <P>MROT is the minimum monthly wage for employees in Russia.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


3.  On the **Types of work incapacity** tab, select one of the following types of incapacity:
    
      - **Illness**
    
      - **Care of sick**
    
      - **Maternity leave**
    
      - **Injury**
    
      - **Treatment in sanatoria and health resorts**
    
      - **Child rearing leave**
    
      - **Child care (out-patient treatment)**
    
      - **Child care (hospitalization)**
    
      - **Child care for child with disability**
    
      - **Child care without restriction of duration**
    
      - **Professional injury**
    
      - **Occupational disease**

4.  In the **Sequence** field, enter the sequence code that refers to the configured counters. The configured counter rules are defined for sick list calculation and payroll transactions creation for the selected type of incapacity.

5.  Select the **Additional payment from Wage Fund** check box to accrue extra pay for the sick lists from the wage fund. This extra pay is paid to the employee to compensate the reduced pay from the social fund that is calculated on the regular average earning.
    
    For example, if an employee is sick, the employee compensation can be calculated based on the average earnings. The employee receives 80 percent of the average earnings guaranteed by law and the company pays the remaining 20 percent as a compensation for work at home during the illness.

6.  In the **Unpaid days** field, select the rate code that corresponds to the number of days at the beginning of the work incapacity that is compensated from the wage fund and not from the social fund.

7.  In the **Benefit limitation** field group, in the **Apply the amount's limitation** field, select the rate code. The rate code that you select must have the **Value** field set to **Yes** in the **Rates** form.
    

    > [!NOTE]
    > <P>You can select the rate code in the <STRONG>Monthly amount limitation</STRONG>, <STRONG>Yearly amount limitation</STRONG>, <STRONG>Daily average earning's amount limitation</STRONG>, and <STRONG>Hourly average earning's amount limitation</STRONG> fields to define rules of limitation based on the prior period’s revenue by using the average earnings calculation.</P>



8.  In the **Apply the seniority's limitation** field, select the rate code. The rate code that you select must have the **Value** field set to **Yes** in the **Rates** form.
    

    > [!NOTE]
    > <P>You can select the rate code in the <STRONG>Minimal seniority for MROT</STRONG>, <STRONG>Seniority limitation</STRONG>, <STRONG>Seniority limitation for dismissal employees</STRONG>, and <STRONG>Seniority limitation for MROT</STRONG> fields to define rules of limitation on the allowance value.</P>



9.  In the **Minimal seniority for MROT** field, select the rate code for limitations that are applied to the employee at the start of the employment. The employee is paid only a fixed percentage of the social insurance at the start of the employment. The rate code value in this field is available based on the rate code values that you select in the **Apply the seniority's limitation** field.
    

    > [!NOTE]
    > <P>The selected rate code applies to the employee’s seniority in months and if the calculated value is positive, you can use the rate value as the percentage of the average earning calculation and the allowance is calculated based on MROT value.</P>



10. In the **Seniority limitation** field, select the rate code for the maximum allowance on the average earning that depends on the seniority. The rate code in this field applies to the employee's seniority in years.
    

    > [!NOTE]
    > <P>The calculated value is used as the percentage of the average earning calculation and the allowance is calculated based on average earning calculated from prior earnings.</P>



11. In the **Seniority limitation for dismissal employees** field, select the rate code for the maximum allowance on the average earnings of an employee after the dismissal of the employee. The rate code in this field applies to the number of days after the employee's dismissal date.
    

    > [!NOTE]
    > <P>If the calculated value is positive, you can use the rate code as the percentage of the average earning to be paid as the allowance. This percentage overrides the value that is defined in <STRONG>Minimal seniority for MROT</STRONG> or <STRONG>Seniority limitation</STRONG> fields.</P>



12. In the **Limitation by days** field, select the rate code to specify limitations for the number of days for which the child-related benefit is calculated. This rate code applies to the selected child's age in years that you set up in the **Relatives** form.

13. In the **Percent** field, select the rate code to specify the percentage at which the compensation is calculated. This rate code applies to the selected child's age in years that you set up in the **Relatives** form.

14. In the **Days restriction for each case** field, select the rate code that specifies the number of days for which the company provides the compensation for a single case. This rate code applies to the selected child's age in years that you set up in the **Relatives** form.

15. In the **Year days restriction** field, select the rate code that specifies the maximum number of days in a year for which the company provides the compensation. This rate code applies to the selected child's age in years that you set up in the **Relatives** form.

16. In the **Calculation method code** field, select a calculation method code for the calculation of the average earnings value for sick list compensation.

17. In the **Time code** field, select the time code to update the timesheet of the employee.

18. In the **Insurance seniority type** field, select the insurance seniority type that indicates the employee absence with a certain code in personified reporting forms that is submitted to the Pension fund.

Use the information in the following table to select the details for calculations of incapacity compensation that are related to child-rearing leave.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Limit of age</strong></p></td>
<td><p>Select a rate code that defines the duration of the payable child care vacation in months. This rate code is used for the vacation payment and for the validation of registration of vacation after you compare the rate value with the child's age at the end of vacation. For more information, see (RUS) Register sick lists manually and calculate compensation.</p></td>
</tr>
<tr class="even">
<td><p><strong>Average duration of month (in days)</strong></p></td>
<td><p>Select the rate code that defines the average number of days in a month that is applied in average earning calculation.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Minimal child care monthly allowance from budget</strong></p></td>
<td><p>Select the rate code that defines the minimum monthly allowance for childcare for employees living in unfavorable conditions. This allowance is funded by the federal budget.</p></td>
</tr>
<tr class="even">
<td><p><strong>Allowance limit (% from budget)</strong></p></td>
<td><p>Select the rate code that defines the percentage of average earnings that is payable as a monthly childcare allowance for employees living in unfavorable conditions. This allowance is funded by the federal budget.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Minimal child care monthly allowance from FSS</strong></p></td>
<td><p>Select the rate code that defines the minimum monthly allowance from the FSS for child care.</p>
<div class="alert">

> [!NOTE]
> <P>FSS is defined as the off-budget fund providing insured individuals with certain social benefits.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Allowance limit (% from FSS)</strong></p></td>
<td><p>Select the rate code that defines the percentage of average earnings that is payable as a monthly childcare allowance from FSS.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Criteria of daily average earning accounting</strong></p></td>
<td><p>Select <strong>Maximum</strong>, <strong>Minimum</strong>, <strong>First</strong>, or <strong>Last</strong> as the criteria for the selection of daily average earnings from the list of daily average earnings in case of simultaneous care of several children.</p></td>
</tr>
<tr class="even">
<td><p><strong>Type of seniority excluded from the insurance one</strong></p></td>
<td><p>Select the code that is used in the personified reporting forms, which is submitted to the pension fund for the period when the allowance is funded by the federal budget for employees living in unfavorable conditions.</p></td>
</tr>
</tbody>
</table>


To set up parameters for the average earnings calculation method for work incapacities allowances calculation, follow these steps:

1.  In the **Sick list calculation settings** form, on the **Overview** tab, either select the existing record or create a new record of the average earning calculation code. For more information, see (RUS) Register sick lists manually and calculate compensation.

2.  On the **Average earnings** tab, select the calculation details for daily or hourly average earnings.

3.  In the **Calculation via funds** field, select the rate code that defines the number of years used for average earnings calculation based on contributions to FSS fund including previous employments.

4.  In the **Number of month** field, select the rate code that specifies the number of months to be used in the average earning calculation. The payment source can be determined from either a wage fund or a health fund for the calculated average earnings.

5.  In the **Calculations** field, select **By salary rate** or **By actual salary** as the calculation principle for sick list calculations.

6.  In the **Calculation type** field, select **By days** or **By hours** to calculate the average earnings.

7.  Select the **Average earnings recalculation** check box to recalculate average earnings for each month of the allowance provision.

8.  Select the **Average rate by MROT recalculation** check box to recalculate average earnings if the allowance is calculated by MROT for each month of the allowance provision.

9.  Enter the required details in the **Numerical parameters**, **Time parameters**, and **Bonus** field groups. For more information see, [(RUS) Set up vacations, business trips, and incentives for the payroll process](rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md) and [(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md).
    

    > [!NOTE]
    > <P>The values in these field groups are applicable only when <STRONG>Number of month</STRONG> field is configured.</P>



## 2\. Create a scale of charges and pay frequencies

You can use the **Scales of charges** form to create a directory of pay scales in an organization. You can create new pay scales, confirm planned pay scales, and cancel confirmed pay scales. After you create a scale of charges, you can define the pay frequencies that depend on the employment status of the employee. The company schedules a minimum of one payroll calculation per month or any number of interim payrolls. The calculation of payrolls depends on government requirements and company policies.

To create a scale of charges, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Structure** \> **Scales of charges**.

2.  Click **New** to create a pay scale.

3.  In the **Code** field, select a code for the list of pay scale codes defined in advance.

4.  In the **Description** field, enter a description of the pay scale.

5.  In the **Start date** field, select the date from which the pay scale is effective.

6.  In the **Wage of first grade** field, enter the minimum wage of the first-grade employee for the selected pay scale.

7.  On the **General** tab, in the **Number of transfer journal** field, you can view the number of the transfer resolution journal that is generated when a pay scale is approved for employees who are hired and paid based on the changed scale of charges.

8.  Optional: Click **Copy** to create a pay scale based on the current pay scale in the **Copying of scale of charges** form.
    
    1.  In the **Code** field, enter a code for the pay scale.
    
    2.  In the **Start date** field, select the starting date for the pay scale.
    
    3.  In the **Factor** field, enter the indexing rate to calculate the wages of the first-grade employee.
    
    4.  Click **OK** to create a pay scale in the **Scales of charges** form.
        

        > [!NOTE]
        > <P>A new pay scale is automatically created in the <STRONG>Scales of charges</STRONG> form. The minimum wage for the previous pay scale is multiplied by the indexing rate value, and the wages for the new pay scale are displayed in the <STRONG>Wage of first grade</STRONG> field.</P>



9.  Click **Grades** to update the salaries and tariff rates for the wage grades of the selected pay scale in the **Wage grades** form.
    
    1.  Click **New** to create a wage grade.
        

        > [!NOTE]
        > <P>You can create a wage grade for any pay scale that is not marked as <STRONG>Active</STRONG>.</P>

    
    2.  In the **Grade** field, enter a numeric code for the wage grade.
    
    3.  In the **Description** field, enter a short description of the wage grade.
    
    4.  In the **Factor** field, enter the indexing rate to calculate the wages of the first grade employee.
        

        > [!NOTE]
        > <P>The minimum wage for the current scale of charges is multiplied by this indexing rate to display the amount in the <STRONG>Salary</STRONG> field.</P>



10. Click **Approval** to open the **Approval of scale of charges** form.

11. In the **Resolution number** field, update the transfer resolution number.

12. In the **Resolution date** field, update the date of issue of the transfer resolution.

13. Click **OK** to close the form.
    

    > [!NOTE]
    > <P>In the <STRONG>Scales of charges</STRONG> form, the <STRONG>Active</STRONG> check box is automatically selected to show the status of the pay scale as approved.</P>



14. Click **Cancellation** to cancel the approval of the pay scale in the **Cancellation of approval of scale of charges** form.

15. Click **OK** to close the form.
    

    > [!NOTE]
    > <P>In the <STRONG>Scales of charges</STRONG> form, the <STRONG>Active</STRONG> check box is cleared automatically to show the cancellation status of the pay scale.</P>



## 3\. Creating types of contracts

Companies hire employee based on rules that are regulated by the labor codes or civil codes. The employees who are hired according to the labor contract laws are additionally classified as **Permanent**, **Temporary**, **On a specific term**, or **Seasonal** types of workers. These types of workers are hired according to the labor agreement. Civil contract workers are not hired permanently by the company, and their work period is for the time period that is specified in the agreement. For more information, see [(RUS) Hire, transfer, and dismiss a worker](rus-hire-transfer-and-dismiss-a-worker.md).

## Next step

[(RUS) Set up parameters for the payroll process](rus-set-up-parameters-for-the-payroll-process.md)

## Related tasks

[(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md)

[(RUS) Set up vacations, business trips, and incentives for the payroll process](rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md)

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
<li><p><strong>Compensation and benefits manager</strong></p></li>
<li><p><strong>Human resource assistant</strong></p></li>
<li><p><strong>Human resource manager</strong></p></li>
<li><p><strong>Payroll administrator</strong></p></li>
<li><p><strong>Payroll manager</strong></p></li>
</ul>
<p>To configure the setup of employee compensation parameters, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitInquire)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitProcessInquire)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Enable compensation process</strong> (HcmJobTypeMaintain)</p></li>
<li><p><strong>Inquire into compensation process</strong> (HcmCompensationInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To configure the setup of employee compensation parameters, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Maintain base payroll information</strong></p></td>
<td><p>HcmPayrollBaisMaintain</p></td>
<td><p>Create scale of charges and pay frequencies.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain pay frequencies</strong></p></td>
<td><p>HRMCompPayFrequencyMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain scale of charges data</strong></p></td>
<td><p>RPayScaleDataMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain injuries and illnesses</strong></p></td>
<td><p>HRMInjurySetupMaintain</p></td>
<td><p>Set up types of work incapacities and injuries.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain injury types</strong></p></td>
<td><p>HRMInjurySetup_InjuryTypeMaintain</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


