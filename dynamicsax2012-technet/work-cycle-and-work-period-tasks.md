---
title: Work cycle and work period tasks
TOCTitle: Work cycle and work period tasks
ms:assetid: 168f59ee-d724-4f28-b74a-1497f4f25ca4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876704(v=AX.60)
ms:contentKeyID: 63385347
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- Fair Labor Standards Act
- FLSA
- Forms.PayrollWorkCycle
- Regular rate of pay
- work cycles
- work cycle
- overtime premium
- work periods
- work period
- overtime premiums
---

# Work cycle and work period tasks 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes the tasks required to set up work cycles and work periods.

You use work cycles to specify the frequency of work periods. Certain earnings, such as the regular rate overtime premiums that are required by the Fair Labor Standards Act (FLSA), are based on work periods and not pay periods.

Work cycles and work periods are set up much like pay cycles and pay periods. After you create work cycles, you generate work periods and assign the work cycles to positions.

The following illustration shows the steps that are required to set up work cycles and work periods. The numbers correspond to the procedures later in this topic.

![Steps for setting up work cycles and work periods](images/Dn876704.Payroll_Work_cycles_and_periods(AX.60).gif "Steps for setting up work cycles and work periods")

## This task is part of a bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time.

For an overview of the process, see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

![Basic steps for setting up Payroll the first time](images/JJ677367.Payroll_Set_up_payroll_basic(AX.60).gif "Basic steps for setting up Payroll the first time")

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
<td><p>Microsoft Dynamics AX 2012 R3 Cumulative Update 8</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
</tbody>
</table>


## 1\. Set up work cycles

Most organizations use only 7-day work periods. There are exceptions, however, and you can create as many work cycles as you need.

To set up work cycles, follow these steps:

1.  Click **Payroll \> Setup \> Work cycles and work periods**.

2.  Click **New**.

3.  Enter the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Information</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Work cycle</strong></p></td>
    <td><p>The unique name or code that you use to identify a work cycle. For example, you might use FLSA standard for a 7-day work cycle that starts on Monday.</p>
    <p>You can’t change the name of the work cycle or the number of days in the work cycle after you create it.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Description</strong></p></td>
    <td><p>A longer name that describes the work cycle. For example, you might use 7-day starts Monday for your organization’s standard work cycle.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Days per period</strong></p></td>
    <td><p>The number of days in the work period. Most organizations use only 7-day work periods. Some positions, such as firefighters, may have 14-day or 28-day work periods.</p>
    <p>You can enter any number of days in this field. If you are using the work period for FLSA compliance, the number must be 7, 14, or 28.</p></td>
    </tr>
    </tbody>
    </table>


Repeat these steps to create additional work cycles. When you have finished, you can close the form or continue with “Generate work periods.”

## 2\. Generate work periods

You can generate any number of work periods for each work cycle. Most organizations generate work periods for one year at a time.

Overtime premiums can be processed only for work periods that are in the system. You should plan to generate new work periods before you use all the existing work periods. Many organizations do this when they prepare for a new fiscal year.

To generate work periods, follow these steps:

1.  Click **Payroll \> Setup \> Work cycles and work periods**.

2.  Select a work cycle.

3.  Click **Generate periods**.

4.  In the **Number of work periods** field, enter the number of work periods to generate.
    
    For 7-day work periods for one year, enter 52. For 28-day work periods for one year, enter 13.

5.  The first time that you generate work periods for a work cycle, in the **First work period start date** field, enter the date of the first day of the first work period that you want to generate. This date is used to determine the first day of all periods that you generate for this work cycle.
    

    > [!NOTE]
    > <P>If you already generated work periods for this work cycle, the <STRONG>First work period start date</STRONG> value is the first calendar day after the last day of the last existing work period. You can’t change this value.</P>
    > <P>There can’t be a gap of any number of days between the ending date of one work period and the starting date of the next work period. Therefore, you can delete only work periods that are at the end of the list of work periods.</P>



6.  Click **Create**.

Repeat these steps to generate work periods for additional work cycles. When you have finished, you can close the form or continue with “Assign work cycles to positions.”

## 3\. Assign work cycles to positions

Work cycles are typically assigned to non-exempt positions when the positions are set up for payroll. For more information, see [Worker and position payroll tasks](worker-and-position-payroll-tasks.md).

To assign a work cycle to a position without modifying any other payroll settings for the position, follow these steps:

1.  Click **Payroll** \> **Common** \> **Positions** \> **Positions**.

2.  Double-click a position to open the **Position** form.

3.  On the **Action Pane**, click **Edit**.

4.  On the **Payroll** FastTab, in the **Work cycle** field, select the work cycle to use for the position.
    

    > [!WARNING]
    > <P>For workers who have more than one position, must make sure that all positions that are assigned to the worker have the same work cycle.</P>



5.  Close the form.

## Next step

The next step is to set up earning codes and earning code groups. For more information, see [Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md).

## Related tasks

[Worker and position payroll tasks](worker-and-position-payroll-tasks.md)

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

> [!NOTE]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up work cycles and work periods, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Set up payroll positions and workers</strong>(PayrollPositionWorkerSetupMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up work cycles and work periods, you must be a member of a security role that includes this privilege:</p>
<ul>
<li><p><strong>Maintain work cycles and periods</strong> (PayrollWorkCycleMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

