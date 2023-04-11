---
title: Worker and position payroll tasks
TOCTitle: Worker and position payroll tasks
ms:assetid: 36582f4f-279c-48a0-a8ce-158eb9b8aef6
ms:mtpsurl: https://technet.microsoft.com/library/JJ677334(v=AX.60)
ms:contentKeyID: 49384108
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- position
- payroll
- worker
- workers
- positions
- worker pay
audience: Application User
ms.search.region: USA
---

# Worker and position payroll tasks 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to set up workers and positions for payroll.

Before you can pay a worker, you must set up payroll information about the worker’s position, taxes, and benefits. This information is used when you generate pay statements for the worker.

In addition, if contribution and deduction amounts are changed on a benefit, that change must be made for each worker who is enrolled in that benefit. For more information, see [Payroll data updates](payroll-data-updates.md).

The following illustration shows the steps that you must follow to set up payroll details for positions and workers. The numbers correspond to the procedures later in this topic.

![Steps to set up payroll for workers and positions](images/JJ677334.Payroll_Set_up_workers_and_positions(AX.60).gif "Steps to set up payroll for workers and positions")

## What do you want to do?

Understand the bigger process

Review the prerequisites

1\. Add payroll details to positions

2\. Add earning codes to worker position assignments

3\. Set up worker tax regions

4\. If required: Change worker residency

5\. Assign default tax regions

6\. Set up worker tax codes

7\. Enroll workers in benefits

8\. Set up payroll information for benefits

Next step

Technical information for system administrators

Find form help

Find related tasks

## Understand the bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time.

For an overview of the process see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

![Basic steps for setting up Payroll the first time](images/JJ677367.Payroll_Set_up_payroll_basic(AX.60).gif "Basic steps for setting up Payroll the first time")

Back to top

## Review the prerequisites

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
<td><p>Microsoft Dynamics AX 2012 R2</p>
<p>Work cycles and work periods require cumulative update 8 for Microsoft Dynamics AX 2012 R3.</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
<tr class="odd">
<td><p>Tasks</p></td>
<td><ul>
<li><p>Union agreements have been set up. For more information, see <a href="https://technet.microsoft.com/library/jj677427(v=ax.60)">Union agreements (form)</a>.</p></li>
<li><p>Positions have been created. For more information, see <a href="key-tasks-new-worker-positions.md">Key tasks: New worker positions</a>.</p></li>
<li><p>Employees are enrolled in a fixed compensation plan. For more information, see “Enroll an employee in a fixed compensation plan” in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a>.</p></li>
<li><p>Benefit eligibility policies have been created. For more information, see <a href="key-tasks-benefit-eligibility-policies.md">Key tasks: Benefit eligibility policies</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## 1\. Add payroll details to positions

You must specify payroll details and add them to a position before you can generate payroll for the position.

To add payroll details to a position, follow these steps:

1.  Click **Payroll** \> **Common** \> **Positions** \> **Positions**.

2.  Double-click a position to open the **Position** form.

3.  On the **Action Pane**, click **Edit**.

4.  On the **Payroll** FastTab, enter this information.
    
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
    <td><p><strong>Pay cycle</strong></p></td>
    <td><p>Select the pay cycle that specifies the payroll calculation frequency and pay date for the position.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Work cycle</strong></p></td>
    <td><p>For non-exempt positions only, select the work cycle that specifies the work periods for the position. Some earnings, such as the regular-rate-of-pay premiums that are required by the Fair Labor Standards Act (FLSA), are based on work periods and not pay periods.</p>
    <p>For exempt positions, leave this field blank.</p>
    <div class="alert">

    > [!WARNING]
    > <P>For workers who have more than one position, make sure that all positions that are assigned to the worker have the same work cycle.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Paid by</strong></p></td>
    <td><p>Select the legal entity that is responsible for making the payroll payments for this position.</p>
    <p>The legal entity that is responsible for paying for the position must be assigned to the position before you can assign worker tax codes to workers.</p>
    <div class="alert">

    > [!NOTE]
    > <P>You can use the <STRONG>Worker</STRONG> form to assign default tax codes for each position. For more information, see <A href="https://technet.microsoft.com/library/hh209054(v=ax.60)">Worker (form)</A>.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Annual regular hours</strong></p></td>
    <td><p>Enter the number of regularly paid hours that the position is expected to have each year. This is used to determine salary adjustments. For example, you might enter 2080 for a regular salaried worker, which equals 40 hours each week. If a worker has eight hours of sick time, the difference of 32 hours can be automatically calculated.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Workers' compensation</strong></p></td>
    <td><p>Click <strong>Add</strong> and select a compensation state and a compensation code. Repeat these steps for any additional workers’ compensation benefits.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Earnings</strong></p></td>
    <td><p>The fields in this group interact in these ways to determine how earnings are generated and shown on earnings statements:</p>
    <ul>
    <li><p>If neither <strong>Generate salary</strong> nor <strong>Generate earnings from schedule</strong> is selected, base earnings statement lines for the position aren’t generated. Only the recurring earnings that are specified in the <strong>Worker</strong> form are generated.</p></li>
    <li><p>If <strong>Generate earnings from schedule</strong> is selected and <strong>Generate salary</strong> is not selected, this information applies:</p>
    <ul>
    <li><p>A schedule is required. You can select from among the calendars that have been created for the legal entity that is selected in the <strong>Paid by</strong> field.</p></li>
    <li><p>A default earning code is required.</p></li>
    <li><p>A day-by-day breakout of earnings for the position is shown in the worker’s earnings statement.</p></li>
    </ul>
    <p>This set of selections is usually used for hourly workers.</p></li>
    <li><p>If <strong>Generate salary</strong> is selected and <strong>Generate earnings from schedule</strong> is not selected, this information applies:</p>
    <ul>
    <li><p>A default earning code is required.</p></li>
    <li><p>The worker is paid the standard position salary amount for each pay period, and a single line is included in the earnings statement. The line will have the date of the last day in the pay period.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If earnings statement lines were entered manually before the earnings were generated, the salary could be split across more than one line. The total of the manually entered lines and the single generated line is always the standard salary amount.</P>


    </div></li>
    </ul>
    <p>This set of selections is usually used for salaried workers.</p></li>
    <li><p>If both <strong>Generate salary</strong> and <strong>Generate earnings from schedule</strong> are selected, this information applies:</p>
    <ul>
    <li><p>A schedule is required. You can select from among the calendars that have been created for the legal entity that is selected in the <strong>Paid by</strong> field.</p></li>
    <li><p>A default earning code is required.</p></li>
    <li><p>The worker is paid the standard position salary amount for each pay period.</p></li>
    <li><p>A day-by-day breakout of earnings for the position is shown on the worker’s earnings statement.</p></li>
    </ul>
    <p>This set of selections is usually used for salaried workers when you want a day-by-day breakout of their time. For example, this might be useful if a worker’s time is associated with a project two days out of five.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


5.  On the **Labor union** FastTab, select the union agreement.

Repeat these steps to set up payroll details for additional positions.

Back to top

## 2\. Add earning codes to worker position assignments

If a worker receives recurring earnings or an earning rate that differs from the default earning code, you must assign an earning code to the worker to make sure that earnings are generated correctly. For more information, see [Generate earnings](generate-earnings.md).

To assign an earning code to a worker, follow these steps:

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Double-click a worker.

2.  On the **Payroll earning codes** FastTab, click **Add** to add an earning code to the worker.

3.  Select the position that the earning applies to.

4.  Select the earning code.

5.  If necessary, change the default amount of the earning code. This value should be appropriate for the rate basis that is displayed.
    
    The rate basis is assigned in the **Earning codes** setup form. For more information, see [Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md).

6.  Select the frequency that the earning is received. For information about how to set up frequencies, see [Payroll calculation frequencies tasks](payroll-calculation-frequencies-tasks.md).
    

    > [!NOTE]
    > <P>If you are setting up an earning code that is based on hours or pieces, the <STRONG>Frequency</STRONG> field isn’t available. Earnings that are based on hours are generated based on the <STRONG>Generate salary</STRONG> and <STRONG>Generate earnings from schedule</STRONG> selections in the <STRONG>Position</STRONG> form. Earnings that are based on pieces are entered manually.</P>



Back to top

## 3\. Set up worker tax regions

When you assign a tax region to a worker, all worker tax codes that apply to the worker are set up automatically. All parameters for the worker tax codes are set to their default values. We recommend that you review the worker tax codes for each worker to make sure that they are accurate. For more information, see [Tax information tasks](tax-information-tasks.md)

To set up tax regions for workers, follow these steps:

1.  Create a list or spreadsheet that contains the following information for each worker that you’re setting up tax regions for:
    
      - The city and state where the worker claims residency
    
      - The city and state of each location where the worker works
    
    In addition, for some states, you need the school district and municipality that are associated with the residence or work locations. Consult the state tax office to determine whether you need this information.

2.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Select a worker. On the **Action Pane**, on the **Payroll** tab, click **Worker tax regions**.

3.  Click **New**.

4.  In the **Tax region** field, select the tax region where the worker claims residency, or the tax region where the worker can work.
    
    The first tax region that is assigned to a worker is designated as the worker’s resident tax region. You can change the worker’s residency at any time. For more information, see “If required: Change worker residency” in this topic.
    
    Most workers have only one worker tax region. A worker who resides in one tax region and works in another tax region has two worker tax regions. A worker who works in multiple locations has multiple tax regions.
    
    In most cases, the worker tax codes that are required for this tax region are automatically assigned to the worker when you close this form. If the worker isn’t assigned to a position, or if the worker’s position isn’t assigned to a legal entity for payroll, the tax codes are assigned later, when the position and legal entity are assigned.

5.  If required by the state that the tax region is in: Select a school district and municipality. If you use both fields, you must select a school district before you can select a municipality.
    
    Consult the state tax office to determine whether this information is required. If it isn’t required, leave these fields blank.

Repeat these steps to assign additional tax regions to the worker. When you finish, close the form.

Back to top

## 4\. If required: Change worker residency

The first tax region that is assigned to a worker is designated as the worker’s resident tax region. A worker can have only one resident tax region at a time. If you know that a worker’s resident tax region will change in the future, you can set up a new resident tax region to take effect on a specified date. The current resident tax region automatically expires when the new one takes effect.


> [!TIP]
> <P>If the resident tax region that you want to change has never been used in a payroll run, you can delete it.</P>



To change the tax region where a worker claims residency, follow these steps:

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Select a worker. On the **Action Pane**, on the **Payroll** tab, click **Worker tax regions**.

2.  Click **Maintain residency**.

3.  Click **Add**.

4.  In the **Tax region** field, select the tax region where the worker claims residency. In the **Effective** field, select the date when the residency becomes effective.
    
    You don’t have to enter an expiration date for the current resident tax region. When you set up a new resident tax region with a new effective date, the expiration date is automatically adjusted for the previous resident tax region.

5.  Close the form. If a message is displayed that states that effective dates for one or more records will be adjusted by the change, click **Yes**.

6.  Verify that the **Resident** check box for the correct tax region is selected, and then close the form.

Back to top

## 5\. Assign default tax regions

*Tax regions* are geographic areas in which a specific set of payroll taxes applies. Tax regions generally correspond to the cities or towns where your workers reside or work. A *worker tax region* is a tax region that has been assigned to a specific worker. A *default tax region* is a worker tax region that is used to generate earnings for a specific position that worker holds.

A default tax region is required for each position that a worker holds. The default tax region is used to generate earnings for a worker’s position. Therefore, if you don’t assign a default tax region to the worker’s position, earnings can’t be generated for the position. To pay the worker, you would have to enter the earnings manually, and then manually enter the tax region on each earning statement line.

If a worker’s position requires different tax regions at different times, you still must select a single default tax region for the position. If necessary, you can change the tax region on individual earning statement lines after you generate earnings for the position.


> [!NOTE]
> <P>Although the default tax region is used to generate earnings for a position, it is assigned to the worker who holds the position, and not to the position itself. If the position is later reassigned to a different worker, a default tax region has to be assigned to that new worker for the position. The default tax region isn’t reassigned to the new worker when the position is reassigned.</P>



To assign a default tax region to a worker, follow these steps:

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Select a worker. On the **Action Pane**, on the **Payroll** tab, click **Default tax region**.

2.  A position can be assigned to only one default tax region. To change the default tax region for a position that already has a default tax region, select the position, and then click **Delete**.
    
    Changes to the default tax region go into effect immediately.

3.  To assign a default tax region to a position, click **New**.

4.  In the **Position** column, select a worker position. One default tax region must be specified for each position that is assigned to the worker.

5.  In the **Tax region** column, select the default tax region for the selected position.
    

    > [!NOTE]
    > <P>If the worker tax region that should be specified for the position isn’t included in the list, close this form and use the <STRONG>Worker tax region</STRONG> form to assign the tax region to this worker. Then, return to this form to assign the default tax region.</P>



Repeat these steps to assign additional default tax regions to the worker’s positions. When you finish, close the form.

Back to top

## 6\. Set up worker tax codes

You can manage a worker’s tax options, such as filing status or total allowances, in the **Worker tax codes** form.

You don’t have to create or assign the worker tax codes because the codes are automatically created and assigned to the worker when you create worker tax regions. At first, all worker tax code parameters are set to their default values. We recommend that you review the worker tax codes for each worker to make sure that they are accurate. For more information, see [Tax information tasks](tax-information-tasks.md).

To set up tax codes for workers, follow these steps:

1.  Create a list or spreadsheet that contains the values of the tax options for all the tax codes that are assigned to each worker whose tax codes you are setting up. These values are different for each tax code. The information is typically collected on IRS Form W-4 or a similar form for the state.

2.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Select a worker. On the **Action Pane**, on the **Payroll** tab, click **Worker tax codes**.
    

    > [!TIP]
    > <P>When the <STRONG>Worker tax codes</STRONG> form opens, the tax codes that are effective on the current date are displayed. To view the tax codes and tax code parameters that were or will be effective on a particular date, click the button next to <STRONG>Current records</STRONG>, enter a date, and then click <STRONG>Apply</STRONG>.</P>



3.  Select a legal entity.
    
    The tax code parameters change to those that are associated with the selected legal entity. Each tax code that is assigned to the worker must be set up for each legal entity.

4.  In the **Tax code** column, select a tax code.

5.  Review each tax code parameter. If the tax code parameter grid is empty, use the form-level **Legal entity** field to select a legal entity.
    
    To change a value, follow these steps:
    
    1.  Click **Maintain versions**.
    
    2.  Select the parameter to change.
    
    3.  In the **Effective** field, enter the date when the new parameter value takes effect.
    
    4.  In the **Value** field, select the new parameter value.
    
    5.  Repeat these steps to change additional parameter values.
    
    6.  When you finish, close the form.
    

    > [!TIP]
    > <P>You can also change the value of the parameter directly in the grid. When you do this, the date is stamped on the new version of the tax code parameter, but the time isn’t. As a result, the first change that you make in a day creates a new version of the parameter. If you change the value later in the same day, the new change overwrites the previous change without creating a new version of the parameter. Only the last change is saved in the date-effective version.</P>



Repeat these steps to configure additional tax codes. If the worker has positions in more than one legal entity, make sure that you set up the worker tax codes for all applicable legal entities.

Back to top

## 7\. Enroll workers in benefits

Go to [Key tasks: Determine benefit eligibility](key-tasks-determine-benefit-eligibility.md) and perform all of the tasks. These tasks include enrolling workers in benefits.


> [!IMPORTANT]
> <P>In Microsoft Dynamics AX, garnishments and tax levies are created and managed by using the benefit framework. Information about how to assign garnishments and tax levies to workers is included in this advanced topic: <A href="garnishment-and-tax-levy-enrollment-tasks.md">Garnishment and tax levy enrollment tasks</A>.</P>



Back to top

## 8\. Set up payroll information for benefits

Payroll information for a benefit isn’t available if the **Payroll impact** field in the **Benefit elements** form is set to **None** for the benefit plan.


> [!NOTE]
> <P>To set up payroll information for a garnishment or tax levy, see <A href="garnishment-and-tax-levy-enrollment-tasks.md">Garnishment and tax levy enrollment tasks</A>.</P>
> <P>Benefit accrual plans, such as paid time off, are not set up or calculated like other benefits. For information about how to enroll a worker in a benefit accrual plan, see <A href="benefit-accrual-plan-tasks.md">Benefit accrual plan tasks</A>.</P>



For more information about how to set up a benefit, see [Benefit setup tasks](benefit-setup-tasks.md). For more detailed information about the fields that are used in this task to set up a benefit for a worker, see [Maintain benefits (form)](https://technet.microsoft.com/library/hh209235\(v=ax.60\)).

To set up payroll information for benefits, follow these steps:

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Select a worker, click **Personal information**, and then click **Benefits**.

2.  Select a benefit from the list of benefits that the worker is enrolled in.

3.  Click the **Payroll details** FastTab. The fields on this FastTab vary, depending on how the **Payroll impact** field in the **Benefit elements** form is set.

4.  Enter this information:
    
      - **Paid by** – The legal entity that pays for the selected benefit for this worker. This is usually the same legal entity that the worker is employed by and that pays for the worker position. For more information, see [Positions (form)](https://technet.microsoft.com/library/aa590982\(v=ax.60\)).
    
      - **Position** – Leave this field blank, except when the total costs for the benefit must follow a specific position. Union dues are an example of a benefit that would be assigned to a position.
        
        If you select a position, the benefit calculations are based only on the earnings from the position. If you don’t select a position, the deductions and contributions for the benefit are calculated, based on all the worker’s earnings. The amounts are split between all the positions that the employee is currently assigned to. The distribution for the deductions and calculations uses the same distribution as the earnings for those positions.
    
      - **Calculation priority** – The order that deductions and contributions for the selected benefit are calculated in, relative to other benefits.
        
        The deductions and contributions for the benefit that has the lowest calculation priority number are calculated first, starting with 0. When multiple benefits have the same number, the calculations for those benefits are completed in alphabetical order.
        
        The calculation order is important when the result of the calculation for one benefit is used in the calculation for another benefit. This is especially likely for garnishments and tax levies. Your legal advisors should help you determine the correct calculation priority for all benefits.
    
      - **Deduction priority** – The order that deductions for the selected benefit are made in, relative to other deductions.
        
        The deduction for the benefit that has the lowest deduction priority number is made first, starting with 1. When multiple benefits have the same number, the deductions for those benefits are made in alphabetical order.
        
        Your legal advisors should help you determine the correct deduction priority for all benefits.
        
        The default value for this field is set up in the **Benefit elements** form. For more information about this field, see [Benefit elements (form)](https://technet.microsoft.com/library/hh209498\(v=ax.60\)).
    
      - **Rate source**, **Basis**, and **Deduction** – The basis option and the deduction amount are used together to calculate the amount of the payroll deduction for the benefit.
        
        The default values for these fields are set up in the **Basis** and **Amount or rate** fields in the **Benefits** form. For information about how these fields interact, see [Benefits (form)](https://technet.microsoft.com/library/jj680907\(v=ax.60\)).
        
        The **Rate source** field determines whether these fields are changed to match the default values when the benefit rates are updated from the benefit.
        
          - If you select **Benefit**, the deduction amount and basis for the worker are updated automatically when you click **Update benefit rates** in the **Benefits** form.
        
          - If you select **Custom**, the deduction amount and basis for the worker aren’t changed when you click **Update benefit rates** in the **Benefits** form. Select this option when the contribution for a worker is specific to that worker, such as when contribution amounts have been grandfathered in for some workers after a rate change.
        

        > [!NOTE]
        > <P>For garnishments and tax levies, the rate source for deductions is always <STRONG>Custom</STRONG>. For other benefit types, the default value in the <STRONG>Rate source</STRONG> field is <STRONG>Benefit</STRONG>.</P>
        > <P>The <STRONG>Rate source</STRONG> field and the <STRONG>Update benefit rates</STRONG> button aren’t available in versions prior to cumulative update 7 for Microsoft Dynamics AX 2012 R2.</P>

    
      - **Rate source**, **Basis**, and **Contribution** – The basis option and the contribution amount are used together to calculate the amount of the employer contribution for the benefit.
        
        The default values for these fields are set up in the **Basis** and **Amount or rate** fields in the **Benefits** form. For information about how these fields interact, see [Benefits (form)](https://technet.microsoft.com/library/jj680907\(v=ax.60\)).
        
        The **Rate source** field determines whether these fields are changed to match the default values when the benefit rates are updated from the benefit.
        
          - If you select **Benefit**, the contribution amount and basis for the worker are updated automatically when you click **Update benefit rates** in the **Benefits** form.
        
          - If you select **Custom**, the contribution amount and basis for the worker are not changed when you click **Update benefit rates** in the **Benefits** form. Choose this option when the contribution for a worker is specific to that worker, such as when contribution amounts have been grandfathered for some workers after a rate change.
        

        > [!NOTE]
        > <P>For contributions, the default value in the <STRONG>Rate source</STRONG> field is <STRONG>Benefit</STRONG>.</P>
        > <P>The <STRONG>Rate source</STRONG> field and the <STRONG>Update benefit rates</STRONG> button aren’t available in versions prior to cumulative update 7 for Microsoft Dynamics AX 2012 R2.</P>

    
      - **Notes** – If you change the default values for any payroll fields in this form, it is a best practice to enter an explanation in this field.

5.  Click the **Payroll limits** FastTab. The FastTab might contain a set of payroll limits for contributions, for deductions, or for both, depending on the value in the **Payroll impact** field in the **Benefit elements** form.

6.  Enter this information for deductions:
    
      - **Limit amount** – The maximum amount that can be deducted from a worker’s pay for the selected benefit. If there is no maximum amount, leave this field blank.
        

        > [!WARNING]
        > <P>The <STRONG>Remaining</STRONG> field displays the amount that can be deducted for the benefit in future pay periods before the end of the limit period is reached. The amount is automatically updated during each pay run. You can also manually change the amount. Because no change history is kept, we recommend that you don’t enter or change the value in this field.</P>

    
      - **Limit period** – The period that the deduction limits apply to. For example, if the limit amount is 1200.00 and the **Limit period** field is set to **Year**, when the cumulative deductions for the benefit reach 1200.00, no additional deductions are allowed for that benefit for the rest of the year.
        
        The last day of the current limit period is displayed in the **Limit end** field. When the current limit period ends, this value in this field is automatically reset to the end of the new limit period.
        

        > [!NOTE]
        > <P>The limit period is based on the calendar. For more information, see <A href="https://technet.microsoft.com/library/hh209498(v=ax.60)">Benefit elements (form)</A>.</P>



7.  Enter this information for contributions:
    
      - **Limit amount** – The maximum amount that can be contributed by the employer for the selected benefit. If there is no maximum amount, leave this field blank.
        

        > [!WARNING]
        > <P>The <STRONG>Remaining</STRONG> field displays the amount that can be contributed for the benefit in future pay periods before the end of the limit period is reached. The amount is automatically updated during each pay run. You can also manually change the amount. Because no change history is kept, we recommend that you don’t enter or change the value in this field.</P>

    
      - **Limit period** – The period that the contribution limits apply to. For example, if the limit amount is 1200.00 and the **Limit period** field is set to **Year**, when the cumulative contributions for the benefit reach 1200.00, no additional deductions are allowed for that benefit for the rest of the year.
        
        The last day of the current limit period is displayed in the **Limit end** field. When the current limit period ends, the value in this field is automatically reset to the end of the new limit period.
        

        > [!NOTE]
        > <P>The limit period is based on the calendar. For more information, see <A href="https://technet.microsoft.com/library/hh209498(v=ax.60)">Benefit elements (form)</A>.</P>



Repeat these steps to set up payroll information for additional benefits. When you finish, close the form.

Back to top

## Next step

If your Payroll setup plan includes entering beginning balances for deductions, benefits, and taxes, see [Payroll beginning balance tasks](payroll-beginning-balance-tasks.md).

After you have completed the basic setup of the Payroll module, advanced setup tasks might be required. For more information, see [Setting up payroll: Advanced topics](setting-up-payroll-advanced-topics.md).

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

> [!NOTE]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up workers and positions for payroll, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Set up payroll positions and workers</strong>(PayrollPositionWorkerSetupMaintain)</p></li>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up workers and positions for payroll, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Maintain benefit setup</strong> (HcmBenefitElementSetupMaintain)</p></li>
<li><p><strong>Maintain benefits</strong> (HcmBenefitInquiryMaintain)</p></li>
<li><p><strong>Maintain position records with an effective date</strong> (HcmPositionDateManagerMaintain)</p></li>
<li><p><strong>Maintain positions using a list page</strong> (HcmPositionListMaintain)</p></li>
<li><p><strong>Maintain positions</strong> (HcmPositionMaintain)</p></li>
<li><p><strong>Update worker date effective information</strong> (HcmWorkerDateManagerEdit)</p></li>
<li><p><strong>Maintain workers</strong> (HcmWorkerMaintain)</p></li>
<li><p><strong>Maintain payroll worker and position detail</strong> (PayrollPositionWorkerSetupMaintain)</p></li>
<li><p><strong>Maintain premium earnings setup</strong> (PayrollPremiumEarningSetupMaintain)</p></li>
<li><p><strong>Update tax data</strong> (PayrollUpdateTaxDatMaintain)</p></li>
<li><p><strong>Maintain work cycles and periods</strong> (PayrollWorkCycleMaintain)</p></li>
<li><p><strong>Maintain benefit accrual plan adjustments</strong> (PayrollWorkerAccrualAdjustMaintain)</p></li>
<li><p><strong>Maintain worker benefit accrual plans</strong> (PayrollWorkerEnrolledAccrualMaintain)</p></li>
<li><p><strong>Expire benefits and worker enrollments</strong> (HcmMassBenefitExpirationEngineServiceRun)</p></li>
<li><p><strong>Maintain the expiration date of benefits and worker enrollments</strong> (HcmMassBenefitExpirationMaintain)</p></li>
<li><p><strong>Update the benefit enrollment rates</strong> (HcmMassBenefitPayrollRateUpdateMaintain)</p></li>
<li><p><strong>Maintain personal contacts</strong> (HcmPersonalContactMaintain)</p></li>
<li><p><strong>Create enrollment date manager</strong> (HcmWorkerEnrollmentDateManagerCreate)</p></li>
<li><p><strong>Delete enrollment date manager</strong> (HcmWorkerEnrollmentDateManagerDelete)</p></li>
<li><p><strong>Update enrollment date manager</strong> (HcmWorkerEnrollmentDateManagerEdit)</p></li>
<li><p><strong>Maintain worker enrollment</strong> (HcmWorkerEnrollmentMaintain)</p></li>
<li><p><strong>Maintain worker mass enrollment</strong> (HcmWorkerMassEnrollmentMaintain)</p></li>
<li><p><strong>Maintain worker garnishment and tax levy rules</strong> (PayrollGarnishmentRuleMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find form help

[Maintain benefits (form)](https://technet.microsoft.com/library/hh209235\(v=ax.60\))

## Find related tasks

[Tax information tasks](tax-information-tasks.md)

[Benefit setup tasks](benefit-setup-tasks.md)

[Garnishment and tax levy setup tasks](garnishment-and-tax-levy-setup-tasks.md)

[Garnishment and tax levy enrollment tasks](garnishment-and-tax-levy-enrollment-tasks.md)

  


