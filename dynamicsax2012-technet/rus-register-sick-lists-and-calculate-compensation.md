---
title: (RUS) Register sick lists and calculate compensation
TOCTitle: (RUS) Register sick lists and calculate compensation
ms:assetid: 702b94d9-0f22-435b-a1de-f9ab5604c196
ms:mtpsurl: https://technet.microsoft.com/library/Dn783346(v=AX.60)
ms:contentKeyID: 62836439
author: Khairunj
ms.date: 08/29/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- Storno
- Forms.RPaySickListTable
- Sick list
- MsDynAx060.Forms.RPaySickListTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Register sick lists and calculate compensation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to register a sick list that indicates that an employee is temporarily incapacitated due to illness, injury, pregnancy, child care, or other reasons.

Sick lists can be registered only for those employees who are insured by the social insurance fund. After the Human Resources department processes sick list registrations, the payroll department can use the sick list registration details to calculate and pay benefits and compensation to employees. Social allowances or compensation for employees can be paid by one of the following three sources:

  - Social insurance fund: When the legal entity hires an employee, the employee is registered with the social insurance fund. When a legal entity pays an employee, the legal entity contributes a certain amount as insurance to the social insurance fund for any incapacity that might happen to the employee in future. When the employee is sick, the legal entity pays the social insurance allowance to the employee and reduces the contribution amount to the social insurance fund.

  - Federal budget: The federal budget pays an allowance to an employee, not for their inability to work, but for other reasons. For example, an employee who is a parent of a child with a disability can receive an allowance from the federal budget. The federal government can ask the social insurance authorities to fund the employee for the allowance amount. Later, the social insurance fund can raise an invoice for the allowance amount to the federal government.

  - Legal entity: The legal entity can voluntarily increase the allowance by paying it from the wage fund. This will compensate the employee for the difference between the social pay and the base salary. The benefit amount is divided across the payment period and the payment sources, such as the social insurance fund or wage fund. After the sick list is added to the salary, it is processed at the start of the sick list calculation.

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
<td><p>Related setup tasks</p></td>
<td><p>To register sick list compensations, the following setup tasks are required:</p>
<ul>
<li><p>Enter the work incapacity parameters for each type of work incapacity in the <strong>Sick list calculation settings</strong> form.</p></li>
<li><p>Set up the length of service in the <strong>Sick list calculation settings</strong> form to determine how long the employee is insured for, and how long the employer pays contributions to the social insurance fund. Also, set up excluded time groups to calculate child care allowances and maternity leave allowances.</p></li>
<li><p>Create rate codes to configure limitations of the social allowances calculation that is a percentage of the calculation based on the current seniority, usage of minimal monthly salary (MROT), and limitations of the base of the calculation of the social allowances.</p></li>
<li><p>Set up time codes for sick lists in the <strong>Timesheet general settings</strong> form. Mark the time codes as special time codes to make sure that the registering sick lists will automatically affect timesheets data. For more information, see the <a href="rus-set-up-employee-compensation-parameters.md">(RUS) Set up employee compensation parameters</a> topic.</p></li>
</ul>
<ul>
<li><p>Set up work schedules in the <strong>Calendar</strong> form including the predefined seven day calendar. The selected calendar will be the official working calendar that is established by the government for each calendar year.</p></li>
<li><p>Set up rates and rate values for sick lists in the <strong>Rates</strong> and <strong>Set up rate values</strong> form.</p></li>
<li><p>Set up counters in the <strong>Counter setup</strong> form.</p></li>
<li><p>Set up the calculation method code for a specific employee in the <strong>Employee average earnings calculation method</strong> form.</p></li>
<li><p>Create social seniority codes in the <strong>Text fields</strong> form.</p></li>
<li><p>Set up calculation sequences for sick list payments and compensations in the <strong>Sequence of calculation</strong> form. For more information, see the <a href="rus-set-up-calculation-procedures-for-the-payroll-process.md">(RUS) Set up calculation procedures for the payroll process</a> topic.</p></li>
</ul>
<ul>
<li><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Calculation procedures</strong> &gt; <strong>Sick lists</strong> &gt; <strong>Sick lists</strong>. click the timesheet update toggle button to the <strong>Timesheet update - Yes</strong> mode to update the timesheet automatically.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Register sick lists

To register sick lists, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Sick lists** \> **Setup** \> **General settings**.

2.  On the **Average earnings** tab, specify **Numerical parameters**, **Time parameters**, and **Bonus** parameters.
    
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
    <td><p><strong>According to schedule</strong></p></td>
    <td><p>Select a time group that defines the work time according to the schedule.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Actually worked</strong></p></td>
    <td><p>Select a time group that defines the time that was actually worked.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>By coefficient</STRONG> in the <STRONG>Calculation method of short month</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Absences from work</strong></p></td>
    <td><p>Select a time group that defines an acceptable reason for an absence from work.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Summary</STRONG> or <STRONG>Calendar</STRONG> in the <STRONG>Calculation method of short month</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>On average</strong></p></td>
    <td><p>Select a time group that defines the time during which the accruals that are entered in the <strong>Average earnings base</strong> field were made.</p></td>
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
    </tbody>
    </table>


3.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Sick lists** \> **Sick lists**.

4.  Click **New** to create a sick list.

5.  On the **Overview** tab, in the **Type of incapacity** field, modify the type of incapacity, if required. The **Calculation method code** field will be updated according to the selected incapacity type.

6.  In the **Calculation method code** field, modify the calculation method code to calculate the sick list average earnings, if required.

7.  Specify an employee code for which the sick list compensation has to be calculated, and the sick list document number.

8.  In the **Number of previous sick list** field, select the number of the previous sick list recorded for the current employee if the employee extends the existing sick list.

9.  In the **Start date** and **End date** fields, select the starting and ending dates for the sick leave period.
    

    > [!NOTE]
    > <P>If you have registered the incapacity type as <STRONG>Child rearing leave</STRONG> and included it in the payroll, you can modify the value in the <STRONG>End date</STRONG> field either manually or through a resolution of early end of childcare vacation.</P>



10. To calculate the sick list compensation you can use the following table to decide what type of calculation and timesheet parameters are necessary.
    
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
    <td><p><strong>Number of month</strong></p></td>
    <td><p>Select the rate code that specifies the number of months to retrieve earnings and working time information for average earnings calculations.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calculation via funds</strong></p></td>
    <td><p>Select the rate code that specifies the number of years to calculate the average earnings. This allows you to retrieve earnings and exclude day details for the average earnings calculation.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If the displayed value is blank or zero, previous average earnings calculations (via prior months’ earnings) will be applied for this sick list.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Calculation type</strong></p></td>
    <td><p>Select <strong>By days</strong> or <strong>By hours</strong> as the calculation type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calculations</strong></p></td>
    <td><p>Select the average-earnings calculation principle for sick list compensation calculation.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>By salary rate</strong></p></li>
    <li><p><strong>By actual salary</strong></p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>The default value in this field is displayed from the <STRONG>Sick list calculation settings</STRONG> or <STRONG>Employee average earnings calculation method</STRONG> form for the employee.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Additional payment from Wage Fund</strong></p></td>
    <td><p>Select this check box to include additional compensation from the wage fund.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Change years for calculation by application</strong></p></td>
    <td><p>Select this check box to use the previous year to obtain the highest average earnings value when the employee submits the application.</p>
    <div class="alert">

    > [!NOTE]
    > <P>It is applicable only when the average earnings calculation for <STRONG>Calculation via funds</STRONG> is selected.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Calculated by MROT</strong></p></td>
    <td><p>Select this check box to allow part or entire sick list compensation to be payable by MROT method.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reduced to MROT</strong></p></td>
    <td><p>Select this check box to reduce the employee’s payment to the minimum salary if the illness happens due to personal negligence.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Treatment violation start date</strong></p></td>
    <td><p>Select the treatment violation starting date for the selected sick list. This is the starting date from which the employee’s payment will be reduced to the minimum salary. For example, the treatment violation can happen due to employee’s violation of the medical treatment regime.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if the <STRONG>Reduced to MROT</STRONG> check box is cleared.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Treatment violation end date</strong></p></td>
    <td><p>Select the treatment violation ending date for the selected sick list.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if the <STRONG>Reduced to MROT</STRONG> check box is cleared.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name of person</strong></p></td>
    <td><p>Select the name of the employee’s child for calculation of deductions, which include relative related allowances. You must select one of the following values in the <strong>Type of incapacity</strong> field:</p>
    <ul>
    <li><p><strong>Child rearing leave</strong></p></li>
    <li><p><strong>Child care (out-patient treatment)</strong></p></li>
    <li><p><strong>Child care (hospitalization)</strong></p></li>
    <li><p><strong>Child care for child with disability</strong></p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>Based on the birth date of the child, the end date for child rearing leave is calculated.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


11. In the **Institution type** field, select **Customer** or **Vendor** as the type of a medical institution.

12. In the **Institution Code** field, select the identification code of the selected institution type that determines the medical organization.

13. On the **Calculation** tab, in the **Salary Report** field group, you can modify the details of prior earnings, if required. You can also define the average earnings period, value, and source details. Based on the selected values, you can view the average earnings details and the recalculated allowance amount details in the **Benefit due** field group.

14. Select the **Add to salary** check box to include the registered sick list in the current payroll calculation.
    

    > [!NOTE]
    > <P>You cannot modify the sick list once it is included in the current payroll calculation</P>



15. Click **Calculation** to define the criteria for starting the sick list calculation procedure to include the total benefit amount in the **Payments and deductions registration** form. Make sure that the sick list compensation calculations also depend on the following criteria:
    
    1.  Rules that are defined for social seniority of the employee. You can define the sick list seniority compensation dates in the **Worker** form.
    
    2.  The years of payment contributions to the social insurance fund.
    
    3.  The period for which the employee is insured under the social insurance fund.

16. Click **Hours worked accounting** to view the work hour details for the employee during the selected calculation period in the **Resulting information about employee worked hours** form. You can click **Payroll lines** and **Bonus** to view transactions that are used for average earnings calculations based on accruals from prior months, which are paid from wage and incentive funds, respectively.

17. You can click **Adjust storno** to process the storno adjustment for the registered sick list number in the prior period’s documents.

## If required: Perform storno adjustment and recalculate the sick lists

The recalculation of sick lists and posting of additional charges are performed if calculation parameters are modified prior to the end date of a sick list. When you use the **Recalculation of sick lists** form, a periodic operation occurs that reports the number of recalculated sick lists created, and compares the recalculated sick list with the initial sick list. Several recalculations may exist for one sick list.

To perform storno adjustment of the registered sick lists, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Sick lists** \> **Sick lists**.

2.  Select the sick list that is included in the payroll in one of the previous payroll periods, and then click **Adjust storno**. The storno sick list is created and automatically added to the current payroll calculation.

3.  Click **Recalculation** to recalculate the payroll and view storno transactions in the results of the payroll calculation.

To generate the sick lists details with storno adjustment details, follow these steps:

1.  Click **Payroll (Russia)** \> **Periodic** \> **Recalculation of sick lists**.

2.  Click **Select** to open the **Inquiry** form, and then enter the selection criteria to recalculate the sick lists that are added to the salary. Click **OK**.

3.  In the **Recalculation of sick lists** form, click **OK** to generate two new recalculation sick list lines that are created for each recalculated sick list in the **Sick lists** form.

## If required: Recalculate modified sick list details and print the sick list report

To recalculate and include the modified sick list details for the employee in the **Recent transactions** form, follow these steps:

1.  Click **Payroll (Russia)** \> **Payroll calculation** \> **Recent transactions**.

2.  Click **New** to create a transaction.

3.  In the **Employee** field, select the employee code.

4.  In the **Procedure code** field, select the calculation procedure code for a sick list.

5.  Click **Recalculate current** to recalculate personal income taxes for only the selected employee.
    
    –or–
    
    Click **Recalculate all** to recalculate personal income tax for all employees.

To print the sick list report, follow these steps:

1.  Select the registered sick list.

2.  Click **Print** to open the **Sick lists report** form.

3.  Select the **Directly to printer** check box to send the sick list details to the printer.

4.  Click **Select** to define the employee average earnings calculation criteria for the specified sick list number.

5.  Click **OK** to print the sick list report.

## Next step

You have registered a sick list. Continue to register related payments, and then continue to manage pay statements. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md).

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
<td><p>To perform this task, you must have the following roles:</p>
<ol>
<li><p>Compensation and benefits manager</p></li>
<li><p>Human resource assistant</p></li>
<li><p>Human resource manager</p></li>
<li><p>Payroll administrator</p></li>
<li><p>Payroll manager</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To register sick lists and calculate compensation, you must be a member of a security role that includes the following the privileges that are described in the following table:</p>
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
<td><p><strong>Maintain injuries and illnesses</strong></p></td>
<td><p>HRMInjurySetupMaintain</p></td>
<td><p>Register sick lists.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain injury or illness incidents</strong></p></td>
<td><p>HRMInjuryIncidentMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain injury types</strong></p></td>
<td><p>HRMInjurySetup_InjuryTypeMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>View injuries and illnesses setup</strong></p></td>
<td><p>HRMInjurySetupView</p></td>
<td><p>Recalculate modified sick list details and print the sick list report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View injury or illness incidents</strong></p></td>
<td><p>HRMInjuryIncidentView</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>View injury types</strong></p></td>
<td><p>HRMInjurySetup_InjuryTypeView</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


