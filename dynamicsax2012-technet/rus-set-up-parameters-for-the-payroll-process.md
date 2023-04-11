---
title: (RUS) Set up parameters for the payroll process
TOCTitle: (RUS) Set up parameters for the payroll process
ms:assetid: d3cf7add-5ac7-433d-8b92-226bb98f9459
ms:mtpsurl: https://technet.microsoft.com/library/Dn435990(v=AX.60)
ms:contentKeyID: 56732190
author: tonyafehr
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- parameter
- parameters
- rate
- funds
- fund
- rates
- posting profiles
- dependencies
- dependency
- Forms.RPayFund
- Forms.RPayGroupTable
- Forms.RPayParameters
- Forms.RPayRateTable
- Forms.RPayRateTrans
- Forms.RPayTable
- Forms.RPayTitlePosting
- pay type
- pay types
- payroll calculation
- payroll group
- payroll groups
- posting profile
- rate value
- rate values
- MsDynAx060.Forms.RPayFund
- MsDynAx060.Forms.RPayGroupTable
- MsDynAx060.Forms.RPayTable
- MsDynAx060.Forms.RPayRateTable
- MsDynAx060.Forms.RPayRateTrans
- MsDynAx060.Forms.RPayParameters
- MsDynAx060.Forms.RPayTitlePosting
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up parameters for the payroll process 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to set up parameters for payroll calculation, payroll groups, rates and dependencies for payroll calculation, payroll posting profiles, pay types, and funds.

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
<li><p>Set up parameters for employee compensation. For more information, see <a href="rus-set-up-employee-compensation-parameters.md">(RUS) Set up employee compensation parameters</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up parameters for payroll calculation

Use the **Payroll parameters** form to set up the parameters for payroll calculation.

To set up parameters for payroll calculation, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Parameters**.

2.  In the **Payroll parameters** form, in the **General** area, specify the calculation date, rounding off details, and terms of payment for payroll.
    
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
    <td><p><strong>Calculation period</strong></p></td>
    <td><p>The period for payroll calculation. After you calculate the payroll and taxes and close the payroll period for the legal entity, the period updates automatically. You can make changes for payroll calculation within this period only.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calculation date</strong></p></td>
    <td><p>Specify a calculation date for the payroll calculation period.</p>
    <div class="alert">

    > [!NOTE]
    > <P>You must select a date within the specified calculation period. For example, if the payroll is calculated monthly, select a date within the month or the ending date of the month.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Funds and data</strong></p></td>
    <td><p>The calculation status of payments to off-budget funds and the employees’ NDFL archive. The options are <strong>Calculated</strong> and <strong>Not calculated</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payroll approximation</strong></p></td>
    <td><p>Enter the precision with which to round off for the payroll amount that is paid to an employee.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Interim payments</strong></p></td>
    <td><p>Select the pay type that is used to register payroll transactions for the interim payments.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Debt of the employee</strong></p></td>
    <td><p>Select the pay type that is used to register payroll transactions for the debt amount for employees at the close of the period.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Debt of the employer</strong></p></td>
    <td><p>Select the pay type that is used to register payroll transactions for the debt amount for the employer at the close of the period.</p></td>
    </tr>
    </tbody>
    </table>


3.  Click **Calculation calendar**, and then in the **Calculation calendar** area, click **New** to create a record for the calculation date. In the **Calculation date** field, specify a calculation date. This date is available in the list of dates that you can select for a specific payroll period in the **Calculation date** field in the **General** area.

4.  Click **Transaction**, and then in the **Transaction** area, set up the compression level for salary transactions, the default payroll posting profile for accounts, and default payroll posting profiles for offset accounts and deferral accounts.
    
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
    <td><p><strong>Compression</strong></p></td>
    <td><p>Specify how to group salary transactions.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Group all transactions</strong> – Group transactions by accounts and financial dimension.</p></li>
    <li><p><strong>Group transactions by table number</strong> – Group transactions for each employee number by account and by financial dimension.</p></li>
    <li><p><strong>All transactions separately</strong> – Do not group accounting transactions.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Account posting profile</strong></p></td>
    <td><p>Select the payroll posting profile for the account that is used to update the account information in the payroll transactions that you create.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Offset account posting profile</strong></p></td>
    <td><p>Select the payroll posting profile for the offset account that is used to update the offset account information in the payroll transactions that you create.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Deferrals posting profile</strong></p></td>
    <td><p>Select the payroll posting profile for the deferral account that is used to update the deferral account information in the payroll transactions that you create.</p></td>
    </tr>
    </tbody>
    </table>


5.  Click **Number sequences**, and then in the **Number sequences** area, set up number sequence codes for the following references:
    
      - Journal
    
      - Timesheet number
    
      - Number of pay-sheets
    
      - Deposit card's number
    
      - Earning wages certificate
    
      - NDFL refund offset voucher
    
      - Document number of bank payment

## 2\. Set up payroll groups

Use the **Payroll groups** form to set up codes for payroll groups and assign employees or workers to the groups. These groups are used to differentiate between the calculation methods for employees or workers based on the information, such as position, date of birth, and gender. You can create a payroll group of workers to define parameters that are specific to workers, such as tax residence or citizenships.

To set up payroll groups, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Payroll groups**.

2.  Click **New** or press CTRL+N to create a payroll group.

3.  In the **Group type** field, select **Worker** or **Employee** as the type of payroll group.

4.  In the **Group** and **Description** fields, enter a name and a description for the payroll group.

5.  Select the **Blocked** check box to indicate that the payroll records of employees or workers in this group must be locked when calculating payroll.

6.  To add employees or workers to the payroll group manually, perform the following steps:
    
    1.  On the **Employees** tab, select the employees or workers to add to the group in the **Remaining employees** list.
    
    2.  Click **\<** to move selected employees or workers. Alternatively, click **\<\<** to move all of the employees or workers.
    
    3.  In the **Period** form, in the **From** and **To** fields, select the starting and ending date for the period for which the employees or workers are added to the payroll group.
    
    4.  Click **OK** to move the selected employees or workers to the **Select employees** list. The number of employees or workers that you move to the **Select employees** list is updated in the **Employees** field on the **Overview** tab.
    
    5.  If required, you can modify the starting and ending date for the period for which an employee or a worker is added to the payroll group after you add the employee or worker to the payroll group. On the **Employees** tab, select the employee or worker in the **Select employees** list, and then modify the starting and ending dates in the **From date** and **To date** fields.
    
    –or–
    
    To add employees or workers to the payroll group using a query, perform the following steps:
    
    1.  Click **Query** \> **Create**, and then specify the criteria to add employees or workers.
    
    2.  Click **OK**, and then click **Yes** to run the query. The employees or workers that match the criteria are added from the **Remaining employees** list to the **Select employees** list on the **Employees** tab. The number of employees or workers that are moved to the **Select employees** list is updated in the **Employees** field on the **Overview** tab. The **Query** check box on the **Overview** tab is selected for the payroll group. A selected check box indicates that the payroll group is created using a query, and that you cannot modify the list of employees or workers in the group manually. You can click **Query** \> **Delete** to delete the query that is attached to a payroll group.
    

    > [!NOTE]
    > <P>You can click <STRONG>Payroll groups</STRONG> on the <STRONG>Payroll</STRONG> tab in the <STRONG>Action pane</STRONG> on the <STRONG>Employees</STRONG> list page to open the <STRONG>Payroll groups</STRONG> form, where you can view the list of groups that an employee or a worker belongs to. You can also assign the employee or worker to another group.</P>



7.  Click **Rates** to open the **Set up rate values** form, where you can set up the salary rates for the payroll group. For more information, see 4. Set up rates based on value type.

You can generate the **Payroll groups** report that contains the details of a selected group of employees or workers. Click **Payroll (Russia)** \> **Reports** \> **Payroll groups**.

## 3\. Set up rates and dependencies for payroll calculation

Use the **Rates** form to define the values of calculation variables, such as the rate to calculate pension fund contributions or the number of children to calculate the corresponding benefits for. You can use the rates to maintain entity specific attributes, such as tax residence status of a worker, base salary value of a hired employee, hazardous working conditions additional pay value for a single department, or a specific social compensation value that is configured for a group of workers.

To set up rates and dependencies for payroll calculation, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Rates**.

2.  Press CTRL+N to create a record.

3.  In the **Rate** and **Name** fields, enter an identification code and name for the rate.

4.  In the **Rate type** field, select the type of rate. Use the information in the following table to decide what type of rate to create.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Rate type</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>System</strong></p></td>
    <td><p>The value of this rate is defined for all of the employees of the legal entity.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Employee</strong></p></td>
    <td><p>The value of this rate is defined for each individual employee separately.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Department</strong></p></td>
    <td><p>The value of this rate is defined for all of the employees in a department.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Group</strong></p></td>
    <td><p>The value of this rate is defined for employees or workers who are part of the payroll group.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Worker</strong></p></td>
    <td><p>The value of this rate is defined for each individual worker separately.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **Value** tab, in the **Value type** field, select a type of value to use for the rate. Use the information in the following table to decide what value to use for the rate.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Type</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Number</strong></p></td>
    <td><p>Enter a numeric value in the <strong>Value</strong> field. This is used as the default value for this rate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Yes/No</strong></p></td>
    <td><p>Select <strong>Yes</strong> or <strong>No</strong> in the <strong>Value</strong> field. This is used as the default value for this rate.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Rate</strong></p></td>
    <td><p>Select a rate in the <strong>Rate</strong> field. This is used to determine the default value for this rate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax deduction</strong></p></td>
    <td><p>Select the income tax deduction, discount, and relief code in the <strong>Deduction code</strong> field. This is used as the default value for this rate.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Criteria</strong></p></td>
    <td><p>Select <strong>Minimum</strong> or <strong>Maximum</strong> as the criteria in the <strong>Value</strong> field.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you select this option, select the <STRONG>Calculation</STRONG> check box to calculate the amount for which the rate is calculated, based on the criterion value that you specified in this field.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Counter</strong></p></td>
    <td><p>Select a counter code in the <strong>Counter</strong> field. This is used as the default value of this rate.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Enum</strong></p></td>
    <td><p>Select an element in the <strong>Element</strong> field. This is used as the default value of this rate.</p>
    <p>You can set up values and descriptions for a list of elements that you can select in the <strong>Element</strong> field. This list of elements is available as options when you manually select a value in the <strong>Element</strong> field. In the lower pane, click <strong>New</strong>, and then in the <strong>Element</strong> and <strong>Description</strong> fields, enter a code and description for the element. This value is used as the default value of this rate.</p></td>
    </tr>
    </tbody>
    </table>


6.  Click **Rate values** to open the **Set up rate values** form, where you can set up the value of the current rate for a specific payroll group, department, or employee for a particular date. For more information, see 4. Set up rates based on value type.

7.  Click **Dependencies** to open the **Dependencies** form, where you can view the counter and statistics statements that use the selected rate.
    

    > [!NOTE]
    > <P>You can open the <STRONG>Dependencies</STRONG> form from the <STRONG>Pay type setup</STRONG>, <STRONG>Counter setup</STRONG>, and <STRONG>Off-budget funds and labor remuneration fund taxes</STRONG> forms. You can view the correlation between module entities, such as rates, pay types, counters, and funds in the <STRONG>Dependencies</STRONG> form.</P>



## 4\. Set up rates based on value type

Use the **Set up rate values** form to set up rates, and then define types and values for rates. You can use the rates to define the values of calculation variables, such as the rate for calculating pension fund contributions or the number of children for calculating the corresponding benefits. You can define the values for the rates for all of the employees in a legal entity, department, or payroll group or for an individual employee.

To set up rates based on value type, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Rate values**.

2.  In the **Rate type** field, select **System**, **Employee**, **Department**, **Group**, or **Worker** to filter the rates displayed in the **Set up rate values** form.

3.  Depending on the value in the **Rate type** field, select a rate code of the selected rate type, and then in the right pane, click **New** to create a value record.

4.  In the **Date** field, select or modify the starting date from which the rate is effective.

5.  Depending on the type of value in the **Value type** field, specify one of the following values for the rate:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Value type</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Number</strong></p></td>
    <td><p>Enter a numeric value in the <strong>Value</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Yes/No</strong></p></td>
    <td><p>Select <strong>Yes</strong> or <strong>No</strong> in the <strong>Value</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Rate</strong></p></td>
    <td><p>Select a rate in the <strong>Rate</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax deduction</strong></p></td>
    <td><p>Select the deduction, discount, and relief code in the <strong>Deduction code</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Criteria</strong></p></td>
    <td><p>Select <strong>Minimum</strong> or <strong>Maximum</strong> as the criteria in the <strong>Value</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Counter</strong></p></td>
    <td><p>Select a counter code in the <strong>Counter</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Enum</strong></p></td>
    <td><p>Select an element in the <strong>Element</strong> field. You can select an element from the list of elements that you define when you create a rate that has a value type of <strong>Enum</strong>.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If you do not specify any value, the value that you specified in the <STRONG>Rates</STRONG> form is used as the default value, except for the rate of type <STRONG>Criteria</STRONG>.</P>



6.  On the **General** tab, in the **Description** field, enter a note about the changes that you made to the rate value.
    

    > [!NOTE]
    > <P>This field is available only for the rates of type <STRONG>Yes/No</STRONG>, <STRONG>Rate</STRONG>, or <STRONG>Criteria</STRONG>.</P>



7.  If an attachment document is available, then in the **Document date**, **Series**, and **Number** fields, specify the date, serial number, and number of the attachment document.

8.  Repeat steps 3 through 7 to create additional values.

## 5\. Set up pay types

Use the **Pay type setup** form to set up the types of pay for employees.

To set up pay types, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Pay types**.

2.  Click **New** or press CTRL+N to create a pay type.

3.  On the **Overview** tab, specify the identification code, name, category, income code, and other details for the pay type.
    
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
    <td><p>Enter an identification code for the pay type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter a name for the pay type.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Category</strong></p></td>
    <td><p>Select <strong>Income</strong> or <strong>Retention</strong> as the category of the pay type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Income code</strong></p></td>
    <td><p>Select the income code for the pay type. For more information about how to set up an income code that is used to calculate income taxes, see “3. Set up an income code for income tax calculations” in <a href="rus-set-up-taxes-and-funds-for-the-payroll-process.md">(RUS) Set up taxes and funds for the payroll process</a>.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Income</STRONG> in the <STRONG>Category</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Posting blocked</strong></p></td>
    <td><p>Select this check box to prevent the posting of transactions that use a pay type that pays directly to the general ledger. When you use the pay type in payroll transactions for an employee, the net salary of the employee is not affected.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Period</strong></p></td>
    <td><p>Select the duration of the period for which an accrual is carried out. This value is used to calculate bonuses for the average earnings calculation for the specified period.</p></td>
    </tr>
    </tbody>
    </table>


4.  On the **Setup** tab, specify the details about entry validation, rate, rounding method, and precision for the pay type that are used to enter data manually in payroll journal lines. For more information, see “1. Create and post a payroll journal” in [(RUS) Generate pay statements](rus-generate-pay-statements.md).
    
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
    <td><p><strong>Entry (quantity)</strong></p></td>
    <td><p>Select this check box to indicate that you can manually enter a value in the <strong>Qty</strong> field in the <strong>Payroll journal lines</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Entry (rate)</strong></p></td>
    <td><p>Select this check box to indicate that you can manually enter a value in the <strong>Rate</strong> field in the <strong>Payroll journal lines</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Entry (amount)</strong></p></td>
    <td><p>Select this check box to indicate that you can manually enter a value in the <strong>Amount</strong> field in the <strong>Payroll journal lines</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rate</strong></p></td>
    <td><p>Select the rate by which the value in the <strong>Qty</strong> field is multiplied to determine the value in the <strong>Amount</strong> field, when you enter lines in the <strong>Payroll journal lines</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Percent value</strong></p></td>
    <td><p>Select this check box to calculate the rate as a percentage of the value in the <strong>Qty</strong> field in the <strong>Payroll journal lines</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rounding</strong></p></td>
    <td><p>Select the value rounding method for the payroll journal lines that use the pay type.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Precision</strong></p></td>
    <td><p>Enter the precision with which to round off the value for the payroll journal lines in the <strong>Payroll journal lines</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Pay type of the current period</strong></p></td>
    <td><p>If required: Select the pay type that is used to write off the deferrals. This information is used for pay types that represent the deferral income for future periods to reference it to the original pay type. Both the pay types are used for applying proper accounting rules when the salary journal transactions are generated.</p></td>
    </tr>
    </tbody>
    </table>


5.  To add the current pay type to the base of calculation or fund, on the **Off-budget fund** tab, select an off-budget fund or calculation base in the **Remaining** list, and then click **\<** to move it to the **Selected** list. Alternatively, click **\<\<** to move all of the off-budget funds to the **Selected** list.
    

    > [!NOTE]
    > <P>This tab is available only if you select <STRONG>Income</STRONG> in the <STRONG>Category</STRONG> field.</P>



6.  On the **Deferrals** tab, in the **Model number** field, select the value model for deferral for the pay type. The name of the value model is updated in the **Name** field.

7.  In the **Deferrals group** field, select the deferral group for the pay type. The name of the value model is updated in the **Name** field.

You can click **Dependencies** to open the **Dependencies** form, where you can view the counter and statistics statements that use the selected pay type.

You can create a copy of a pay type by clicking **Copy**, and then in the **Pay type** field, specify an identification code for the pay type.

## 6\. Set up off-budget and labor remuneration funds

Use the **Off-budget funds and labor remuneration fund taxes** form to set up a group of pay types that are used as off-budget funds, tax bases for income tax calculation, or basis for the calculation that defines the structure of payment types that are used to calculate sick pay, vacation pay, maintenance payments, and other payments. You can also select a list of pay types that are used as limits of calculations, such as the maximum percentage of personal deduction to apply to the net salary of an employee.

  - **Off-budget fund** – This fund defines the tax base that is used to calculate the actual contributions of employees to the off-budget funds.

  - **Basis for calculation** – This fund defines the base for calculation of vacation pay, sick pay, maintenance payments, other payments, and tax and personal deductions. The fund also defines the limit of calculations.

To set up off-budget and labor remuneration funds, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Calculation** \> **Funds**.

2.  Click **New** or press CTRL+N to create a fund record.

3.  In the **Fund type** field, select **Off-budget fund** or **Basis for calculation** as the type of fund.

4.  In the **Fund code** and **Name** fields, enter an identification code and a name for the fund record.

5.  If you select **Off-budget fund** in the **Fund type** field, perform the following steps:
    
    1.  In the **Account type** and **Account** fields, select the type and code of the account to post the off-budget funds payments to.
    
    2.  In the **Offset account type** and **Offset account** fields, select the type and code of the offset account to post the off-budget funds payments to.
    
    3.  On the **General** tab, in the **Account type** and **Deviation account** fields, select the type and code of deviation account. The deviation account is used to post the differences in off-budget funds payments that occur if you recalculate the funds for a previous period and the base of the recalculation is changed and cannot be determined.
    
    4.  Set up the financial dimensions for the account, deviation account, and offset account.

6.  On the **Pay types** tab, select a pay type in the **Remaining** list, and then click **\<** to move it to the **Selected** list. Alternatively, click **\<\<** to move all of the pay types to the **Selected** list.

You can click **Dependencies** to open the **Dependencies** form, where you can view the counter and statistics statements that use the selected fund.

You can click **Funds totals** to open the **Payments to off-budget funds (totals)** form, where you can view the information about total payments to off-budget funds.


> [!NOTE]
> <P>The <STRONG>Funds totals</STRONG> button is available only for the fund of type select <STRONG>Off-budget fund</STRONG>.</P>



You can set up off-budget funds that are used to calculate the individual contributions. For more information, see “5. Set up off-budget funds for individual contribution calculations” in [(RUS) Set up taxes and funds for the payroll process](rus-set-up-taxes-and-funds-for-the-payroll-process.md).

## 7\. Set up payroll posting profiles

Use the **Payroll posting profiles** form to set up posting profiles for payroll calculation.

To set up a payroll posting profile, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Payroll posting profiles**.

2.  Click **New** or press CTRL+N to create a posting profile.

3.  In the **Posting profile** and **Description** fields, enter an identification code and description for the posting profile.

4.  On the **Settings** tab, click **New** to create a record, and then specify the grouping that is used for posting profile, pay type of an employee, job title of an employee, and account details.
    
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
    <td><p><strong>Cost type relation</strong></p></td>
    <td><p>Select the pay type or counter code to apply the posting profile to.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Table</strong> – Apply the posting profile to a pay type.</p></li>
    <li><p><strong>Group</strong> – Apply the posting profile to a calculation base.</p></li>
    <li><p><strong>All</strong> – Apply the posting profile to all of the pay types.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Cost type/Base for calculation</strong></p></td>
    <td><p>Select the pay type or calculation base that the current posting profile line applies to. This field is determined by the selections in the <strong>Cost type relation</strong> field.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Cost type relation</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Employee relation</strong></p></td>
    <td><p>Select the employee code to apply the posting profile to.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Table</strong> – Apply the posting profile to an employee.</p></li>
    <li><p><strong>Group</strong> – Apply the posting profile to a payroll group.</p></li>
    <li><p><strong>All</strong> – Apply the posting profile to all of the employees.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Employee/Payroll group</strong></p></td>
    <td><p>Select the employee or payroll group that the current posting profile line applies to. This field is determined by the selections in the <strong>Employee relation</strong> field.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Employee relation</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Department code</strong></p></td>
    <td><p>Select the department code to apply the posting profile to.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Position</strong></p></td>
    <td><p>Select the position to apply the posting profile to.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Account type</strong></p></td>
    <td><p>Select the type of account that is used in the payroll transactions that are generated for employees according to the conditions that you set up.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Account</strong></p></td>
    <td><p>Select the account code that is used in the payroll transactions that are generated for employees according to conditions that you set up.</p></td>
    </tr>
    </tbody>
    </table>


5.  Repeat step 4 to configure additional settings.

6.  On the **Financial dimensions** tab, set up the financial dimension codes for accounts for each posting profile line.

## Next step

You have finished setting up the general parameters for the payroll process. Continue to set up additional parameters for the payroll process. For more information, see the following topics:

  - [(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md)

  - [(RUS) Set up payments, journals, and deductions for the payroll process](rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md)

  - [(RUS) Set up vacations, business trips, and incentives for the payroll process](rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md)

After you have finished all of the setup tasks for the payroll process, continue to calculate payments for workers. For more information, see the following topics:

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
<td><p>To set up parameters for the payroll process, you must be a member of a security role that includes the following duties.</p>
<ul>
<li><p><strong>Maintain worker master</strong> (HcmWorkerMaintain)</p></li>
<li><p><strong>Enable payroll process</strong> (HcmPayrollProcessEnable)</p></li>
<li><p><strong>Enable organizational process</strong> (HcmOrganizationalProcessEnable)</p></li>
<li><p><strong>Enable time management process</strong> (RPayTimeManageProcessEnable)</p></li>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Enable collections process</strong> (CollectionLetterCollectionsProcessEnable)</p></li>
<li><p><strong>Maintain and configure organizational model</strong> (OMOrganizationsMaintain)</p></li>
<li><p><strong>Inquire into payroll process</strong> (HcmPayrollProcessInquire)</p></li>
<li><p><strong>Inquire into compensation process</strong> (HcmCompensationInquire)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitProcessInquire)</p></li>
<li><p><strong>Inquire into organizational process</strong> (HcmOrganizationalProcessInquire)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Inquire into human resources process</strong> (RPayHumanResourcesProcessInquire)</p></li>
<li><p><strong>Maintain earning entry</strong> (PayrollEarningStatementGenerationMaint)</p></li>
<li><p><strong>Enable project accounting process</strong> (ProjProjectAccountingProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitInquire)</p></li>
<li><p><strong>Inquire into payroll position and worker setup</strong> (PayrollPositionWorkerSetupInquire)</p></li>
<li><p><strong>Inquire into workers</strong> (HcmWorkerInquire)</p></li>
<li><p><strong>Maintain audit policies</strong> (ComplianceMgmtAuditPoliciesMaintain)</p></li>
<li><p><strong>Maintain project master</strong> (ProjProjectMasterMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up parameters for the payroll process, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p><strong>Edit workers</strong> (HcmWorkerEdit)</p></li>
<li><p><strong>Maintain accounting rules (references to posting profiles &amp; transactions compression)</strong> (RPayAccRulesMaintain)</p></li>
<li><p><strong>Maintain bank document posting profiles</strong> (RPayPostProfileMaintain)</p></li>
<li><p><strong>Maintain base payroll information</strong> (HcmPayrollBaisMaintain)</p></li>
<li><p><strong>Maintain department rates values</strong> (RPayDepRatesMaintain)</p></li>
<li><p><strong>Maintain department rates values</strong> (RPayRateValuesMaintain)</p></li>
<li><p><strong>Maintain groups of pay types (funds)</strong> (RPayFundGroupMaintain)</p></li>
<li><p><strong>Maintain organizational chart</strong> (RPayOrgChartMaintain)</p></li>
<li><p><strong>Maintain pay types</strong> (RPayTypeMaintain)</p></li>
<li><p><strong>Maintain rates list</strong> (RPayRatesListMaintain)</p></li>
<li><p><strong>Maintain teams</strong> (OMTeamMaintain)</p></li>
<li><p><strong>View bank document posting profiles</strong> (RPayPostingProfilesView)</p></li>
<li><p><strong>View base payroll information</strong> (HcmPayrollBasisView)</p></li>
<li><p><strong>View department rates values</strong> (RPayRateValuesVIew)</p></li>
<li><p><strong>View department rates values</strong> (RPayDepRatesView)</p></li>
<li><p><strong>View employees rates values</strong> (RPayEmplRatesView)</p></li>
<li><p><strong>View groups of pay types (funds)</strong> (RPayFundGroupView)</p></li>
<li><p><strong>View pay types</strong> (RPayPayTypesView)</p></li>
<li><p><strong>View persons rates values</strong> (RPayPersonalRatesValuesView)</p></li>
<li><p><strong>View rates dependencies</strong> (RPayRatesDependView)</p></li>
<li><p><strong>View rates list</strong> (RPayRatesListView)</p></li>
<li><p><strong>View the list of dependent elements</strong> (RPayDependentListView)</p></li>
<li><p><strong>View workers</strong> (HcmWorkerView)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


