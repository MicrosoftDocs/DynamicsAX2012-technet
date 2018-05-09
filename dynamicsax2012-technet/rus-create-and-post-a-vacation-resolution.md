---
title: (RUS) Create and post a vacation resolution
TOCTitle: (RUS) Create and post a vacation resolution
ms:assetid: c5d1ac7f-f56e-4393-a40e-50ba40486ec0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn435957(v=AX.60)
ms:contentKeyID: 56730929
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RHRMOrderTable
- Forms.RHRMOrderTrans
- childcare vacation
- Forms.RHRMLeaveScheduleTable
- vacation resolution
- vacation schedule
- MsDynAx060.Forms.RHRMOrderTable
- MsDynAx060.Forms.RHRMOrderTrans
- MsDynAx060.Forms.RHRMLeaveScheduleTable
---

# (RUS) Create and post a vacation resolution 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create and confirm a vacation resolution before an employee can be granted vacation time. You can create a resolution line manually or by using a vacation schedule in the **Vacation resolution lines** form. The vacation resolution is used by the payroll department to pay the employee for the vacation. You can also create a vacation resolution for an employee who returns early to work from a childcare vacation.

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
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p>Configuration tasks</p></td>
<td><ul>
<li><p>Create vacation type codes. For more information, <a href="rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md">(RUS) Set up vacations, business trips, and incentives for the payroll process</a>.</p></li>
<li><p>Create a calendar that can be used as a work schedule for employees. For more information, see &quot;Create a calendar&quot; in <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
<li><p>Assign time codes for vacation. For more information, see &quot;Assign time codes to a special time account&quot; in <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
<li><p>Create calculation sequences for vacation time earnings, vacation payment and compensation. For more information, see &quot;Set up a vacation calculation method&quot; in <a href="rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md">(RUS) Set up vacations, business trips, and incentives for the payroll process</a>.</p></li>
</ul>
<p></p></td>
</tr>
</tbody>
</table>


## 1\. Create a vacation resolution manually

You can use the **Vacation resolution** form to create a resolution line manually. The vacation resolution is used by the payroll department to pay the employee for the vacation.

To create a vacation resolution manually, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Vacations**.

2.  Click **New** or press CTRL+N to create a new vacation resolution journal.

3.  On the **Overview** tab, in the **Name** field, select the journal name.

4.  In the **Resolution date** field, select the resolution creation date.

5.  Click **Lines** to open the **Vacation resolution lines** form.

6.  Click **New** or press CTRL+N to create a new vacation resolution line.

7.  On the **Overview** tab, specify the following details.
    
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
    <td><p><strong>Employee</strong></p></td>
    <td><p>Select an employee code. The name of the employee is automatically displayed in the <strong>Employee name</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Type of vacation</strong></p></td>
    <td><p>Select the type of vacation.</p></td>
    </tr>
    </tbody>
    </table>


8.  On the **General** tab, specify the following details.
    
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
    <td><p><strong>Period start</strong></p></td>
    <td><p>Select the default starting date of the working period.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>End of period</strong></p></td>
    <td><p>Select the default ending date of the working period.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The vacation is earned by the employee for this working period. You can also print the vacation balance of an employee in the <STRONG>Balance of vacation days</STRONG> report. For more information, see <A href="rus-vacation-business-trip-and-sick-list-reports.md">(RUS) Vacation, business trip, and sick list reports</A>.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Start date</strong></p></td>
    <td><p>Select the starting date of the vacation.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Quantity of days</strong></p></td>
    <td><p>The number of vacation days.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The end date of the vacation is automatically displayed in the <STRONG>End date</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>End date</strong></p></td>
    <td><p>Select the ending date of the vacation.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The number of the vacation days is automatically displayed in the <STRONG>Quantity of days</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document number</strong></p></td>
    <td><p>The number of the original document that grants the vacation.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Document date</strong></p></td>
    <td><p>The date of the original document that grants the vacation.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The document argument details are displayed from the <STRONG>Document-arguments</STRONG> form, where the employee request for vacation is registered. The vacation schedule details are displayed from the <STRONG>Vacation schedule</STRONG> form when the vacation resolution is created from it.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


9.  Click **Validate** to validate the resolution lines, and then click **OK** in the **Check journal** form.
    

    > [!NOTE]
    > <P>The time period of the vacation resolution lines for an employee must not overlap with each other, or with the time periods for sick lists and business trips that are already registered for the employee. You must resolve the conflict before you can validate the resolution.</P>



10. Click **Post** to post the journal, and then click **OK** in the **Post journal** form.
    

    > [!NOTE]
    > <P>The <STRONG>Posted</STRONG> check box is automatically selected in the <STRONG>Vacation resolution</STRONG> form.</P>



You can cancel the posted journal when you need to update the vacation resolution or correct a mistake in the vacation resolution.

1.  Click **Restore** to cancel the journal posting in the **Post journal** form.

2.  Click **OK** to cancel the journal posting. You must cancel the related payments in the resolution journal, and then cancel the journal posting.

To print the statutory reports, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Reports** \> **Form T-7**. to print the vacation schedule report.

2.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Vacations**.

3.  Click **Print** \> **Form T-6a** to print the vacation resolution report for employees.

4.  To print the vacation resolution report for an employee, click **Lines** to open the **Vacation resolution lines** form, and then click **Print** \> **Form T-6**.

To view the posted vacation resolution lines for an employee, in the **Employees** form, on the **Employment** tab, click **Vacations**.

## 2\. Create a vacation resolution using a vacation schedule

You can create a vacation resolution using a vacation schedule. A vacation schedule contains information about annual paid vacations that are allocated to an employee for a calendar year, and is the basis for the vacation resolution. You can use the **Vacation schedule** form to create a vacation schedule.

To create a vacation schedule, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Periodic** \> **Vacation schedule**.

2.  Click **New** or press CTRL+N to create a new vacation schedule.

3.  In the **Years** field, modify the creation year of the vacation schedule, if necessary.
    

    > [!NOTE]
    > <P>By default, this field displays the year that follows the current calendar year. The vacation schedule document number is automatically displayed in the <STRONG>Document number</STRONG> field in the <STRONG>Vacation resolution lines</STRONG> form when the resolution line is created for the scheduled vacation that refers to the vacation schedule line.</P>



4.  In the **Formation date** field, select the creation date of the vacation schedule.

5.  Click **Lines** to open the **Vacation schedule lines** form.

6.  Click **New** or press CTRL+N to create a new vacation schedule line, and then on the **Overview** tab, specify the following details.
    
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
    <td><p><strong>Employee</strong></p></td>
    <td><p>Select an employee code.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Type of vacation</strong></p></td>
    <td><p>Select the type of vacation.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Start date</strong></p></td>
    <td><p>Select the starting date of the vacation.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Quantity of days</strong></p></td>
    <td><p>The number of vacation days.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The ending date of the vacation is displayed in the <STRONG>Finish date</STRONG> field based on the starting date and the number of vacation days.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


To create a vacation resolution from a vacation schedule, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Vacations**.

2.  Repeat steps 2 through 5 from the "Create a vacation resolution manually" section.

3.  In the **Vacation resolution lines** form, click **Creating from schedule** to open the **Creating order lines on the basis of vacation schedule** form.

4.  Select the required vacation schedule, and then click **Add**.
    

    > [!NOTE]
    > <P>The vacation schedule lines for the selected employee are automatically added to the vacation resolution in the <STRONG>Vacation resolution lines</STRONG> form.</P>



5.  Repeat steps 9 through 10 from the "Create a vacation resolution manually" section.

## 3\. Create a vacation resolution to reimburse an employee for early return from a childcare vacation

Use the **Early end of childcare vacation** form to create a vacation resolution for an employee who returns early to work from a childcare vacation.

When an employee registers for a childcare vacation, the employee is paid from the social insurance fund for the period of absence, and the timesheet of the employee resumes from the day of return. The employee is paid along with the allowances from the social insurance fund. When the resolution is posted, the end date of the registered childcare vacation is changed based on the date that is entered in the resolution.

## Next step

(RUS) Configure standard deductions calculation

(RUS) Register vacations, business trips, and calculate compensation

(RUS) Register sick lists manually and calculate compensation

## Related tasks

[(RUS) Generate pay statements](rus-generate-pay-statements.md)

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
<li><p><strong>Human resources assistant</strong></p></li>
<li><p><strong>Human resources manager</strong></p></li>
<li><p><strong>Payroll assistant</strong></p></li>
</ul>
<p>To create a vacation resolution, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create a vacation resolution, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Maintain vacations resolution</strong></p></td>
<td><p>RPayVacResolutionMaintain</p></td>
<td><p>Create a vacation resolution manually.</p></td>
</tr>
<tr class="even">
<td><p><strong>View vacations resolution</strong></p></td>
<td><p>RPayVacResolutionView</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain vacation schedules</strong></p></td>
<td><p>RPayVacScheduleMaintain</p></td>
<td><p>Create a vacation resolution using a vacation schedule.</p></td>
</tr>
<tr class="even">
<td><p><strong>View vacation schedules</strong></p></td>
<td><p>RPayVacSchedulesView</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

