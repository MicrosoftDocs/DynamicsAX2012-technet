---
title: (RUS) Create a timesheet for an employee
TOCTitle: (RUS) Create a timesheet for an employee
ms:assetid: 649b0972-eb97-48fa-ac51-4ab5d0029a46
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn452006(v=AX.60)
ms:contentKeyID: 56713182
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- department
- timesheet
- Forms.SysQueryForm
- Forms.RHRMOrderTable
- Forms.RPayTblDayHourTrans
- Forms.RPayTblJournal
- employee timesheet
- timesheet adjustment
- timesheet journal
- MsDynAx060.Forms.SysQueryForm
- MsDynAx060.Forms.RHRMOrderTable
- MsDynAx060.Forms.RPayTblDayHourTrans
- MsDynAx060.Forms.RPayTblJournal
---

# (RUS) Create a timesheet for an employee 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create a timesheet for an employee in the current payroll period after the employee is hired. You can make manual adjustments to a timesheet that was created for an earlier payroll period retroactively using the current timesheet for the current payroll period.

The timesheet creation process starts at the beginning of the new payroll period. Timesheet details can be added or updated during the employee hiring process. You can create a timesheet to measure the planned hours for an employee, and to register employee working hours against the planned hours. Timesheets are generated automatically using work schedules, which are created by using calendars, and assigned to employees as terms of their employment.

You can also view cumulative information that pertains to employee working hours, vacations, sick leave, and business trips.

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
<td><p>Configuration tasks</p></td>
<td><ul>
<li><p>Create departments for the organization. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Create time codes, time groups, and payment form codes. For more information, see <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Transactions</p></td>
<td><p>Create an employee. For more information, see <a href="rus-create-a-worker.md">(RUS) Create a worker</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Create a timesheet journal for a department

You can create a timesheet journal for a department. This journal contains timesheets for individual employees within the department.

To create a timesheet journal for a department, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Timesheet journal**.

2.  Click **New** to create a timesheet journal.

3.  In the **Reporting period** field, select the reporting period for the timesheet.

4.  On the **Overview** tab, specify the following details for the timesheet.
    
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
    <td><p><strong>Department code</strong></p></td>
    <td><p>Select the department code.</p>
    <div>

    > [!NOTE]
    > <P>The timesheet is generated for the employees in this department.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payment form</strong></p></td>
    <td><p>Select the payment form code. The payment form determines whether the employee is paid monthly, weekly, daily, or hourly.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Revenue recognition accounting rule</strong></p></td>
    <td><p>Select the type of accounting rule that applies to the timesheet from the following options:</p>
    <ul>
    <li><p><strong>Daily</strong> – The number of working hours is recorded daily.</p></li>
    <li><p><strong>Summarized</strong> – The number of working hours is recorded in a monthly summary.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


5.  On the **General** tab, select the pay rates for the employee in the **Rate 1**, **Rate 2**, and **Rate 3** fields.
    

    > [!NOTE]
    > <P>These rates are used in counters to calculate the time-related payment for an employee.</P>



6.  Select the **Online calculation** check box to automatically calculate the employee payment when you create or change the timesheet lines.

7.  Click **Timesheet lines**, and then click **Daily** to open the **Timesheet generation** form.

8.  Click **Yes** to add the timesheet lines to the timesheet journal in the **Timesheet (daily)** form.

## 2\. Create an employee timesheet manually in a timesheet journal for a department

You can add the employee record lines manually to the timesheet journal for a department.

To create a timesheet journal manually for a department, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Timesheet journal**.

2.  Click **New** to create a timesheet journal for a department and enter the required details on the **Overview** and **General** tabs.

3.  Click **Timesheet lines**, and then click **Daily** to open the **Timesheet generation** form.

4.  In the **Timesheet generation** form, click **No** to open the **Timesheet (daily)** form.

5.  In the **Timesheet (daily)** form, click **Add lines** to open the **Add record to timesheet** form.

6.  In the **Add record to timesheet** form, in the **Calculation period** field, select the calculation period.

7.  Click **Select** to open the **Timesheet** form.

8.  Click **Add** to add the employee detail lines, and then select the required information in the **Field** and **Criteria** fields.

9.  Click **OK** to view the employee timesheet in the **Timesheet (daily)** form.

## 3\. If required: Create a timesheet journal with employee timesheets

You can create a timesheet to process a payment for an employee in a department for the current payroll period or for a future payroll period. The type of payment that you assign determines the payroll calculation for the employee. When you create a timesheet journal for departments, specify the payment form code and the monthly salary rate code for the payroll calculation.

To create a timesheet journal that includes employee timesheets for a department, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Timesheet journal**.

2.  Click **Timesheets generation** to open the **Timesheets generation** form.

3.  To add the criteria to create timesheets for departments, click **Select** to open the **Timesheets generation** form.
    

    > [!NOTE]
    > <P>You can use the default query or modify the query as required to generate the timesheet.</P>



4.  Click **OK** to close the form.

5.  In the **Timesheets generation** form, click **OK** to view the generated timesheet journal details in the **Timesheet journal** form.

You can view the generated payroll transactions and print the required statutory documents for the created timesheet in the **Timesheet journal** form.

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Timesheet journal**.

2.  In the **Timesheet journal** form, click **Payroll lines** to open the **Timesheet** form, where you can view the generated payroll transactions.

3.  Click **Print** to print the required statutory documents for the created timesheet. For more information, see [(RUS) Payroll accounting reports](rus-payroll-accounting-reports.md).

You can view the cumulative working hours for an employee in the **Resulting information about employee worked hours** form.

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Hours worked accounting**.

2.  In the **Resulting information about employee worked hours** form, view the cumulative working hours for an employee.

## 4\. Optional: Create a timesheet for an employee during the employment process

You can create a timesheet for an employee during the hiring process. You can specify the format in which the payment is made and the calendar schedule for the employee in the **Worker** form.

To create a timesheet for an employee during the hiring process, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Create a worker. For more information, see [(RUS) Create a worker](rus-create-a-worker.md).

3.  On the **Action pane**, click **Edit**, and then click the **Payroll** tab.

4.  In the **Payment form** field, select the format in which the payment is made.

5.  In the **Calendar** field, select the calendar type to create a timesheet for an employee.

6.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Employment**.

7.  Click **New** to create an employment resolution journal.

8.  Select the journal number, and then click **Lines** to open the **Employment resolution lines** form.

9.  Select the employee, and then click **Post** to post the resolution journal order that is given by human resources personnel for hiring.

10. Click **Yes** to create or update the timesheet for the employee. You can update a timesheet for an employee during other employment related processes, as well. For example, you can do this during dismissal and transfer resolution posting.

## 5\. Adjust a timesheet for a previous period

You can make manual adjustments to a timesheet that was created for an earlier payroll period retroactively using the current timesheet for the current payroll period.

To adjust a timesheet for an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Timesheet journal**.

2.  Select the timesheet number, and then click **Timesheet lines** to open the **Timesheet (daily)** form.

3.  On the **Hours** tab, select the employee that you are making the adjustment for.

4.  Click **Add lines** to record hours for an earlier period and add them to the current timesheet.

## Next step

[(RUS) Generate pay statements](rus-generate-pay-statements.md)

## Related tasks

[(RUS) Create and post a vacation resolution](rus-create-and-post-a-vacation-resolution.md)

[(RUS) Create and post a business trip resolution](rus-create-and-post-a-business-trip-resolution.md)

(RUS) Register vacations, business trips, and calculate compensation

(RUS) Register sick lists manually and calculate compensation

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
<li><p><strong>Human resources administrator</strong></p></li>
<li><p><strong>Payroll administrator</strong></p></li>
<li><p><strong>Compensation &amp; benefits manager</strong></p></li>
</ul>
<p>To create a timesheet for an employee, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable time management process</strong> (RPayTimeManageProcessEnable)</p></li>
<li><p><strong>Inquire into time management process</strong> (RPayTimeProcessInquire)</p></li>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
<li><p><strong>Enable project accounting process</strong> (ProjProjectAccountingProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitInquire)</p></li>
<li><p><strong>Inquire into payroll position and worker setup</strong> (PayrollPositionWorkerSetupInquire)</p></li>
<li><p><strong>Inquire into workers</strong> (HcmWorkerInquire)</p></li>
<li><p><strong>Maintain audit policies</strong> (ComplianceMgmtAuditPoliciesMaintain)</p></li>
<li><p><strong>Maintain project master</strong> (ProjProjectMasterMaintain)</p></li>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create a timesheet for an employee, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Maintain time sheet journals</strong></p></td>
<td><p>RPayTimeSheetJourMaintain</p></td>
<td><p>Create a timesheet journal for a department.</p></td>
</tr>
<tr class="even">
<td><p><strong>View time sheet journals</strong></p></td>
<td><p>RPayTimeSheeJournView</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

