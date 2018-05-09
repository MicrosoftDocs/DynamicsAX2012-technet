---
title: Pay cycle and pay period tasks
TOCTitle: Pay cycle and pay period tasks
ms:assetid: 0029649f-b8fd-447f-87ba-618598329257
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677318(v=AX.60)
ms:contentKeyID: 49384091
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- pay periods
- pay cycles
- pay cycle
- pay period
- Forms.PayrollPayCycle
- MsDynAx060.Forms.PayrollPayCycle
---

# Pay cycle and pay period tasks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes the tasks that are required to set up pay cycles and pay periods.

A pay cycle determines how often payroll is run and on what specific days workers are paid. For example, a pay cycle might be monthly and employees might be paid on the last day of the month, or it might be weekly and employees might be paid on the Tuesday following the end of the pay period.

Pay cycles are assigned to positions to control when workers in those positions are paid. Pay cycles are also assigned to the payroll calculation frequencies that determine the schedule for processing payroll elements, such as benefits or recurring earnings.

After you create pay cycles, you can generate pay periods for each cycle. Each pay period includes a default payment date that is based on information that you provide. However, you can modify the default payment date in a pay period to allow for exceptions, such as when the payment date falls on a holiday.

The following illustration shows the steps that you must follow to set up pay cycles and pay periods. The numbers correspond to the procedures later in this topic.

![Steps for creating pay cycles and pay periods](images/JJ677318.Payroll_Pay_cycles_and_periods(AX.60).gif "Steps for creating pay cycles and pay periods")

## What do you want to do?

Understand the bigger process

Review the prerequisites

1\. Set up pay cycles

2\. Generate pay periods

3\. Optional: Modify the payment dates and statuses of pay periods

4\. Assign pay cycles to positions

Next step

Technical information for system administrators

Find related tasks

## Understand the bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time.

For an overview of the process, see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

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
<td><p>Microsoft Dynamics AX 2012 R2</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
</tbody>
</table>


Back to top

## 1\. Set up pay cycles

Use pay cycles to specify the frequency of pay periods and the pay dates for positions.

Before you set up pay cycles, determine how many unique combinations of pay cycle frequencies and pay dates you have in your organization. Each unique combination requires a separate pay cycle.

For example, you might have the following pay cycle frequencies and pay dates in your organization.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Position type</p></th>
<th><p>Pay cycle frequency</p></th>
<th><p>Pay dates</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Management</p></td>
<td><p>Semimonthly</p></td>
<td><p>The first day and the fifteenth day of the month</p></td>
</tr>
<tr class="even">
<td><p>Salary, non-management</p></td>
<td><p>Weekly</p></td>
<td><p>The last day of the pay period</p></td>
</tr>
<tr class="odd">
<td><p>Hourly</p></td>
<td><p>Weekly</p></td>
<td><p>The Friday following the last day of the pay period</p></td>
</tr>
</tbody>
</table>


In this case, your organization would require three pay cycles. One of the three pay cycles would then be assigned to every position.

To set up pay cycles, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Pay cycles and pay periods**.

2.  Click **New**.

3.  In the **Pay cycle** field, enter the name of the pay cycle. For example, you might enter mgt for the semimonthly pay cycle for management or w-s for the weekly pay cycle for salaried positions.
    

    > [!NOTE]
    > <P>You can’t change the name of a pay cycle after you save it. If you haven’t yet used it, you can delete it and try again.</P>



4.  In the **Description** field, enter a few words to describe the pay frequency. For example, you might enter weekly salaried non-management for the weekly pay cycle for salaried positions.

5.  In the **Pay cycle frequency** field, select the frequency to associate with this pay cycle. The following pay cycle frequencies are available:
    
      - **Daily**
    
      - **Weekly**
    
      - **Biweekly**
    
      - **Semimonthly**
    
      - **Monthly**
    
      - **Quarterly**
    
      - **Semiannually**
    
      - **Annually**
    
    Different groups of positions that have the same pay cycle frequency might have different pay dates. For example, both hourly and salaried positions might be paid biweekly. If all positions are paid on the Friday following the last working day of the pay period, you can use the same pay cycle for both hourly and salaried positions. However, assume that the salaried positions are paid on the last working day of the pay period, and the hourly positions are paid on the Friday following the last working day of the pay period. In that case, you would need one biweekly pay cycle for the hourly positions, and another biweekly pay cycle for the salaried positions.
    

    > [!TIP]
    > <P>You can’t change the pay cycle frequency after you save the pay cycle. Instead, you would create a new pay cycle that has the correct pay cycle frequency.</P>



Repeat these steps to create additional pay cycles. When you have finished, close the form, or continue with “Generate pay periods.”

Back to top

## 2\. Generate pay periods

You can generate any number of pay periods for each pay cycle. Most organizations generate pay periods for one year at a time.


> [!NOTE]
> <P>Pay can be processed only for pay periods that are in the system. You should plan to generate new pay periods before you use all the existing pay periods. Many organizations do this when they prepare for a new fiscal year.</P>
> <P>There can’t be a gap of any number of days between the ending date of one pay period and the starting date of the next pay period. Therefore, you can delete only pay periods that are at the start or at the end of the list of pay periods.</P>



To generate pay periods, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Pay cycles and pay periods**.

2.  Select a pay cycle.

3.  Click **Generate**.

4.  In the **Number of periods** field, enter the number of pay periods to generate.
    
    The following table lists the number of pay periods that you would enter to generate pay periods for one year or five years for common pay cycle frequencies.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Pay cycle frequency</p></th>
    <th><p>Pay periods in one year</p></th>
    <th><p>Pay periods in five years</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Monthly</p></td>
    <td><p>12</p></td>
    <td><p>60</p></td>
    </tr>
    <tr class="even">
    <td><p>Semimonthly</p></td>
    <td><p>24</p></td>
    <td><p>120</p></td>
    </tr>
    <tr class="odd">
    <td><p>Biweekly</p></td>
    <td><p>26</p></td>
    <td><p>130</p></td>
    </tr>
    <tr class="even">
    <td><p>Weekly</p></td>
    <td><p>52</p></td>
    <td><p>260</p></td>
    </tr>
    </tbody>
    </table>


5.  The first time that you generate pay periods for a pay cycle, in the **First period start date** field, enter the date of the first day of the first pay period that you want to generate. This date is used to determine the first day of all periods that you generate for this pay cycle.
    
    If you have already generated pay periods for this pay cycle, the **First period start date** value is the first calendar day after the last day of the last existing pay period. You can’t change the value.

6.  In the **First payment date** field, enter the pay date for the first pay period. This date is used to determine the default payment date for all pay periods that you generate for this pay cycle. For example, if this date occurs five days after the starting date of the first pay period, the default payment date will always be five days after the starting date of each pay period.

7.  Click **Create**.

8.  Repeat steps 2 through 7 to generate pay periods for additional pay cycles.

When you have finished, you can close the form or continue with “Modify the payment dates and statuses of pay periods.”

If you don’t want to modify default payment dates at this point, the pay cycles are ready for you to use. You can assign the pay cycles to positions to control when workers in those positions are paid. To do this, see “Assign pay cycles to positions” later in this topic.

You can also assign the pay periods that are associated with each pay cycle to the payroll calculation frequencies that determine the schedule for processing payroll elements, such as benefits or recurring earnings. To do this, see “Assign pay periods to payroll calculation frequencies” in [Payroll calculation frequencies tasks](payroll-calculation-frequencies-tasks.md).

Back to top

## 3\. Optional: Modify the payment dates and statuses of pay periods

When you generate pay periods, the pay period status is **Open**, and a default payment date is set for every pay period. After you generate pay periods, you can set the pay period status according to your organization’s practices, and you can change any default payment dates that are bank holidays or other days when pay can’t be issued.


> [!TIP]
> <P>You might find it helpful to have a list of weekend and holiday dates before you start this task.</P>



To modify payment dates and the statuses of pay periods, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Pay cycles and pay periods**.

2.  Select a pay cycle.

3.  Review all the dates in the **Default payment date** column. Change any dates on which payments can’t be made.
    
    If you prefer, you can change the payment date when you generate pay statements.

4.  Optional: Change the pay period status according to your organization’s practices.
    
    When you change the pay period status to **Closed**, payments and pay statements for the closed pay period can’t be processed.
    
    Some organizations change the status of all pay periods to **Closed** as soon as the pay periods are generated. They change the status of a pay period to **Open** to generate pay statements for the pay period, and then change the status back to **Closed** after pay statements are submitted for payment.
    
    Other organizations change the status only after payments are issued. And some organizations never change the status.

5.  For each date that you change, in the **Comments** column, enter the reason for the change.

6.  Repeat steps 2 through 5 to modify payment dates for additional pay cycles.

7.  Close the form.

When you have finished, the pay cycles are ready for you to use. You can assign the pay cycles to positions to control when workers in those positions are paid. To do this, continue with “Assign pay cycles to positions.”

You can also assign the pay periods that are associated with each pay cycle to the payroll calculation frequencies that determine the schedule for processing payroll elements, such as benefits or taxes. To do this, see “Assign pay periods to payroll calculation frequencies” in [Payroll calculation frequencies tasks](payroll-calculation-frequencies-tasks.md).

Back to top

## 4\. Assign pay cycles to positions

Pay cycles are typically assigned to positions when the positions are set up for payroll. For more information, see [Worker and position payroll tasks](worker-and-position-payroll-tasks.md).

To assign a pay cycle to a position without modifying any other payroll settings for the position, follow these steps.

1.  Click **Payroll** \> **Common** \> **Positions** \> **Positions**.

2.  Double-click a position to open the **Position** form.

3.  On the **Action Pane**, click **Edit**.

4.  On the **Payroll** FastTab, in the **Pay cycle** field, select the pay cycle that specifies the payroll frequency and pay date for the position.

5.  Close the form.

Back to top

## Next step

If you have to control which pay periods various payroll elements are processed in, you must set up payroll calculation frequencies. For more information, see [Payroll calculation frequencies tasks](payroll-calculation-frequencies-tasks.md).

If you decide not to set up payroll calculation frequencies, the next step is to set up work cycles and work periods. Certain earnings, such as the overtime premiums that are required by the Fair Labor Standards Act (FLSA), are based on work periods and not pay periods. For more information, see [Work cycle and work period tasks](work-cycle-and-work-period-tasks.md).

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
<td><p>To set up pay cycles and pay periods, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up pay cycles and pay periods, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Maintain pay cycles and create pay periods</strong> (PayrollPayCycleMaintain)</p></li>
<li><p><strong>Maintain payroll calculation frequencies</strong> (PayrollCalculationFrequencyMaintain)</p></li>
<li><p><strong>Maintain work cycles and periods</strong> (PayrollWorkCycleMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find related tasks

[Worker and position payroll tasks](worker-and-position-payroll-tasks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

