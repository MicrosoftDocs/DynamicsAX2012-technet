---
title: Work schedule and leave tasks
TOCTitle: Work schedule and leave tasks
ms:assetid: 4e4b241d-04fc-4e73-bdc0-b18442fac70a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677338(v=AX.60)
ms:contentKeyID: 49384112
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- schedule
- calendar
- leave
- schedules
- family leave
- paid leave
- unpaid leave
- work calendar
- maternity leave
- work schedule
- calendars
- medical leave
- work calendars
- work schedules
audience: Application User
ms.search.region: USA
---

# Work schedule and leave tasks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes the tasks required to set up work schedules and leave types.

Even though you use the same form to maintain the calendars that are used by both Payroll and Production, we recommend that you maintain separate calendars for Payroll and for Production control.

A seven-day pattern of hours that are ordinarily worked is called a working time template. After you create a working time template for each schedule that hourly workers in your organization typically work, you can use the template to generate a working time calendar of one year or more. When you specify the working time calendar as the schedule for a position, all workers who are assigned to the position use that schedule. The scheduled hours are used to generate the default earnings statement lines for the worker-position combination.

Schedules that are based on working time calendars are also used with leave types for paid leave, for both hourly workers and salaried workers.

The following illustration shows the steps that you must follow to set up work schedules and leave. The numbers correspond to the procedures later in this topic.

![Setup steps for work schedules and leave](images/JJ677338.Payroll_Work_schedules_and_leave(AX.60).gif "Setup steps for work schedules and leave")


> [!NOTE]
> <P>Time off that is part of a benefit accrual plan, such as vacation time or sick time, is not considered to be leave. For more information about benefit accrual plans, see <A href="benefit-accrual-plan-tasks.md">Benefit accrual plan tasks</A>.</P>



## What do you want to do?

Understand the bigger process

Review the prerequisites

1\. Create working time templates

2\. Create working time calendars

3\. Create leave types

4\. Put a worker on leave

Next step

Technical information for system administrators

Find form help

Find related tasks

## Understand the bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time. For information about additional tasks required for this step in the process, and an overview of the whole process, see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

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

## 1\. Create working time templates

Create a working time template for each schedule that hourly workers in your organization typically work.

To create a working time template, follow these steps:

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Working time templates**.

2.  Click **New**.

3.  On the **Overview** tab, enter a brief identifier and a descriptive name for the template.

4.  On the **Monday** tab, do the following:
    
      - Make sure that the **Closed for pickup** check box is not selected.
    
      - Enter the regular hours of operation for Mondays. Use the **From** field to specify the time that the work period starts. Use the **To** field to specify the time that the work period ends.
        

        > [!TIP]
        > <P>To set up a 24-hour calendar, enter 12:00 am in the <STRONG>From</STRONG> field and 24 in the <STRONG>To</STRONG> field.</P>

    
      - In the **Efficiency** field, enter a value other than 0 (zero). Typically, you would enter 100 to represent that the worker is on duty at that time.
        

        > [!TIP]
        > <P>To enter a time period that the user does not receive pay for, such as the lunch hour, enter 0 (zero) in the <STRONG>Efficiency</STRONG> field for the line. No earnings will be generated for that line.</P>

    
      - Leave the **Property** field blank.

5.  Repeat the previous step for the remaining days of the week.
    
    Or, to copy the same schedule to a different day, click **Copy day** and select the weekdays to copy from and to. Leave the **Copy property** check box blank.

Repeat these steps to create additional working time templates. When you have finished, close the form.

Back to top

## 2\. Create working time calendars

A working time calendar defines the typical schedule for a position. You can use the calendar to generate default earnings statement lines for workers who are assigned to the position.

To create a working time calendar, follow these steps:

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Calendars**.

2.  Click **New** to create a line.

3.  In the **Calendar** field, enter a unique identifier of up to 10 characters.
    
    You might want to use the same first character for every payroll calendar identifier so that they are sorted together in this form.

4.  In the **Name** field, enter a descriptive name.

5.  Click **Working times**, and then click **Compose working times** to create or update working times for the calendar.

6.  In the **Calendar** field, select the name of the calendar to compose working times for.

7.  In the **From date** and **To date** fields, enter the first date and the last date to compose working times for. By default, the calendar starts on the current date and ends on the date that is one year from the current date.

8.  In the **Working time template** field, select the appropriate template.

9.  Click **OK**.

10. When earnings are generated from a schedule, the default earning code for the position is used. There might be days in the calendar that should use a different earning code. For example, holidays might use a Double time earning code.
    
    For any day in the calendar that requires a different earning code, select the day in the upper grid and then enter the earning code in the lower grid.
    

    > [!NOTE]
    > <P>The earning codes that you enter here must have a unit of measure of <STRONG>Hours</STRONG> in the <STRONG>Earning codes</STRONG> form.</P>



Repeat these steps to create additional working time calendars for payroll.

After you create working time calendars, you can assign them to positions. For more information, see [Worker and position payroll tasks](worker-and-position-payroll-tasks.md).

Back to top

## 3\. Create leave types

You use leave types to set up the types of leave that workers can take, such as medical, educational, or parental leave.

Time off that is part of a benefit accrual plan, such as vacation time or sick time, is not considered to be leave. For more information about benefit accrual plans, see [Benefit accrual plan tasks](benefit-accrual-plan-tasks.md).

Before you create leave types that can be used to generate earning statement lines for paid leave, you must create an earning code for each type of paid leave. For more information, see [Earning code examples](earning-code-examples.md).

When a worker goes on leave, the leave type, together with the start date and end date for the leave, is recorded in the **Leave** form.

To create a leave type, follow these steps:

1.  Click **Human resources** \> **Setup** \> **Workers** \> **Leave types**.

2.  Click **New**.

3.  Enter a name and description for the leave type.

4.  If required, enter the earning code to use when earnings lines for the leave are generated.
    
      - For paid leave, earning codes are required. The earnings lines that are generated for the position during the leave will show a daily breakout.
    
      - For unpaid leave, if you don’t enter any earning codes, no earnings lines will be generated during the leave period, and the salary amount will be adjusted, although you can manually modify the earnings statement to add earnings statement lines.
        
        If you want an unpaid leave to generate earning lines, you can create a zero-rate earning code and assign that earning code to the leave type. This allows for hours to be tracked in payroll for time on leave, which lets you generate pay statements. These statements will have no pay, but you can force deduction arrears, track time on leave in Payroll, and allow for FMLA hours taken to be updated by Payroll.

Repeat these steps to create additional leave types. When you have finished, close the form.

Back to top

## 4\. Put a worker on leave

Schedules are used together with leave types when a worker is on paid leave. When a worker is on a paid leave, you must assign a schedule to the worker’s position in order to incorporate the leave settings when you generate earnings statements for the worker. This is required even if you generate earnings by salary for that position and not from a schedule. A schedule is optional for a salaried worker who is on unpaid leave.

Time off that is part of a benefit accrual plan, such as vacation time or sick time, is not considered to be leave. For more information about benefit accrual plans, see [Benefit accrual plan tasks](benefit-accrual-plan-tasks.md).

To put a worker on leave, follow these steps:

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to put on leave.

3.  On the **Action Pane**, click **Employment**, and then click **Leave**.

4.  In the **Leave type** field, select the type of leave.

5.  In the **Start date** and **End date** fields, enter the first and last dates of the leave.

6.  In the **Note** field, enter information about the leave.

7.  Close the form.

8.  For a paid leave, if the worker holds a salaried position, verify that a schedule is assigned to the position.
    
    1.  On the **Action Pane**, click **Worker position assignments**. In the **Position assignments** form, click the number in the **Position** column.
    
    2.  In the **Position** form, click the **Payroll** FastTab.
    
    3.  If the **Schedule** field is blank, click **Edit**, and then select a schedule. If there is a schedule in the **Schedule** field, close the form.

9.  Repeat the previous step for any additional salaried positions that the worker holds.

Back to top

## Next step

The next step is to set up benefit accrual plans. For more information, see [Benefit accrual plan tasks](benefit-accrual-plan-tasks.md).

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
<td><p>To set up calendars, work schedules, and leave, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Enable workforce management process</strong> (HCMWorkforceProcessEnable)</p></li>
<li><p><strong>Maintain calendar master</strong> (WorkCalendarMasterMaintain)</p></li>
<li><p><strong>Enable calendar management process</strong> (WorkCalendarsEnable)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up calendars, work schedules, and leaves, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Maintain payroll worker and position detail</strong> (PayrollPositionWorkerSetupMaintain)</p></li>
<li><p><strong>Maintain leave types</strong> (HcmLeaveTypeMaintain)</p></li>
<li><p><strong>Maintain worker employment leave records</strong> (HCMEmploymentleavemaintain)</p></li>
<li><p><strong>Copy calendar working times</strong> (WorkCalendarCopy)</p></li>
<li><p><strong>Create working times</strong> (WorkCalendarCreate)</p></li>
<li><p><strong>Maintain working times</strong> (WorkCalendarDateMaintain)</p></li>
<li><p><strong>Delete calendar working times</strong> (WorkCalendarDeleteProcess)</p></li>
<li><p><strong>Maintain calendars</strong> (WorkCalendarTableMaintain)</p></li>
<li><p><strong>Copy working hours of days</strong> (WorkTimeCopyDay)</p></li>
<li><p><strong>Delete calendar working times</strong> (WorkCalendarDeleteProcess)</p></li>
<li><p><strong>Copy working time templates</strong> (WorkTimeCopy)</p></li>
<li><p><strong>Copy working hours of days</strong> (WorkTimeCopyDay)</p></li>
<li><p><strong>Maintain working time templates</strong> (WorkTimeTableMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find form help

[Working times (form)](https://technet.microsoft.com/en-us/library/aa553844\(v=ax.60\))

[Positions (form)](https://technet.microsoft.com/en-us/library/aa590982\(v=ax.60\))

[Position action (form)](https://technet.microsoft.com/en-us/library/jj729764\(v=ax.60\))

[Leave (form)](https://technet.microsoft.com/en-us/library/aa588994\(v=ax.60\))

## Find related tasks

[Worker and position payroll tasks](worker-and-position-payroll-tasks.md)

  


