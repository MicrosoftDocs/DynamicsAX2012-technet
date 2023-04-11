---
title: (RUS) Configure parameters for time management
TOCTitle: (RUS) Configure parameters for time management
ms:assetid: 2e0d0002-c1b5-465a-93c1-7363f452aafc
ms:mtpsurl: https://technet.microsoft.com/library/Dn452005(v=AX.60)
ms:contentKeyID: 56713176
author: tonyafehr
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- calendar
- timesheet
- Forms.RPayCalendarTable
- Forms.RPayCalendarTimeTable
- Forms.RPayFormTypeTable
- Forms.RPayHolidays
- Forms.RPayTblParameters
- Forms.RPayTimeGroupTable
- payment form
- public holiday
- special time account
- time codes
- time group
- time management
- MsDynAx060.Forms.RPayCalendarTable
- MsDynAx060.Forms.RPayCalendarTimeTable
- MsDynAx060.Forms.RPayFormTypeTable
- MsDynAx060.Forms.RPayTblParameters
- MsDynAx060.Forms.RPayHolidays
- MsDynAx060.Forms.RPayTimeGroupTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Configure parameters for time management 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create a list of time codes for working time, overtime, idle time, vacation, sick leave, business trips, and different kinds of overtime.

Timesheets record daily working hours or a summary of working hours for a specified period. You can set up time codes for a timesheet and indicate whether they are for hourly or daily work. These time codes can be associated with time groups that allow you to track actual working hours for an employee, and absences from work.

You can specify how payment is made to an employee whether the employee is paid monthly, weekly, daily, or hourly. You can also set up the working schedule for employees by using calendars.

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
<td><p>Configuration task</p></td>
<td><p>Rates for payroll calculation that are used for employment process must be configured. For more information, see <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Configure general settings for timesheet

You can use the **Timesheet general settings** form to configure the timesheet parameters for time codes, timesheet rates, or timesheets that you generate.

To configure the default general settings for a timesheet, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Setup** \> **Setup**.

2.  On the **General** tab, in the **Hours/days** field, select **Hours only**, **Days only**, or **Days and hours** as the default method to register the time codes.

3.  In the **Revenue recognition accounting rule** field, select **Daily** or **Summarized** as the default method to register timesheets.

4.  Select the **Online calculation** check box to specify that the payments that are related to the timesheet are calculated automatically when you make changes to the timesheet.

5.  In the **Rate 1**, **Rate 2**, and **Rate 3** fields, select the timesheet rates as the default rates.

6.  In the **Human resource manager** field, select the employee who is responsible for the creation of the timesheet.

## 2\. Create a list of time codes

You can create time codes to represent working time, idle time, vacation, sick leave, business trips, and two types of overtime. The types of overtime are payable overtime and non-payable overtime. For payable overtime, employees are paid according to a calculation sequence for every two hours beyond the regular working schedule, and are paid double-time for working on a holiday. For non-payable overtime, working extra hours increases the vacation days for employees.

To create time codes for a timesheet, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Setup** \> **Time code list**.

2.  Click **New** to create a time code.

3.  On the **Overview** tab, in the **Time code** field, enter the time code.

4.  In the **Name** field, enter a name for the time code.

5.  In the **Hours/days** field, select **Hours only**, **Days only**, or **Days and hours** to modify the method to register time codes, if required.

6.  On the **General** tab, in the **Short description** field, enter a short description for the time code.

7.  In the **Sequence** field, select the calculation sequence that contains counters, where calculation rules are defined to calculate multiple payments for the selected time codes. For more information about counter setup, see "Set up counters for calculation sequences" in [(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md).

## 3\. Assign time codes to a special time account

You can assign time codes to special time accounts for vacation time, sick list time, or business trip time. The special time account is used to track the employee absence during the creation of the timesheet. For more information, see the RUS) Register vacations, business trips, and calculate compensation and (RUS) Register sick lists manually and calculate compensation topics.

To assign time codes to a special time account, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Setup** \> **Setup**.

2.  In the **Timesheet general settings** form, on the **Special times account** tab, in the left pane, select **Vacation** for the special time account.

3.  In the right pane, press CTRL+N, and then select a time code for the vacation time account in the **Time code** field.
    

    > [!NOTE]
    > <P>You can also select <STRONG>Sick list</STRONG> or <STRONG>Business trip</STRONG> for the special time accounts, and then define their time codes in the <STRONG>Time code</STRONG> field.</P>



4.  Select the **Update** check box to update the time for the default line that is created when you generate a timesheet.

## 4\. Create time groups

You can create time groups and assign similar time codes for each time group.

To create time groups, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Setup** \> **Time group**.

2.  Click **New** to create a time group.

3.  On the **Groups** tab, in the **Group code** field, enter the code for the time group.

4.  In the **Short description** field, enter a short description for the time group.

5.  On the **Time codes** tab, in the **Time codes** field, select the time codes to be added to the time group.

6.  Click **\<** to transfer the selected time code to the **Selected** field.
    

    > [!NOTE]
    > <P>You can click <STRONG>&lt;&lt;</STRONG> to transfer all of the time codes from the <STRONG>Time codes</STRONG> field to the <STRONG>Selected</STRONG> field.</P>



## 5\. Create a payment form and assign a list of time codes

The way that an employee is paid, whether it’s monthly, weekly, daily, or hourly, is referred to as the form of payment. You can create these different forms of payment and assign the applicable list of time codes.

## Create a payment form

To create a payment form, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Setup** \> **Timesheet** \> **Payment form**.

2.  Click **New** to create a payment form.

3.  On the **Overview** tab, in the **Payment form** field, enter the code for the payment form.

4.  In the **Name** field, enter a name for the payment form.

5.  Close the form.

## Assign time codes to payment forms

To assign a list of time codes to each payment form, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Setup** \> **Timesheet** \> **Time codes**.

2.  In the **Payment form** field, select the payment form to which you want to assign the time codes.

3.  Click **New** to assign a list of time codes that are applicable to the payment form.
    
    Use the information in the following table to assign the time codes to a payment form.
    
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
    <td><p><strong>Time code</strong></p></td>
    <td><p>Select the time code.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Hours/days</strong></p></td>
    <td><p>Modify the method to register time codes, if required.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Sequence</strong></p></td>
    <td><p>Select the sequence of calculation for the selected time code.</p></td>
    </tr>
    </tbody>
    </table>


## 6\. Create a list of public holidays

You can create a list of public holidays in the **Holidays** form.

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Calendar** \> **Holidays**.

2.  Click **New** to create a holiday.

3.  In the **Date** field, enter a holiday date.

4.  To indicate that it is a holiday, in the **Type of day** field, select **Holiday**.
    

    > [!NOTE]
    > <P>The list of public holidays for the specified calendar period allows you to create calendars with holidays when you select the <STRONG>Holiday accounting</STRONG> check box in the <STRONG>Calendars setup</STRONG> form.</P>



## 7\. Create a calendar and copy the schedule

You can set up calendars that can be used later as working schedules for employees.

To create a calendar, follow these steps:

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Calendar** \> **Calendars setup**.

2.  Click **New** to create a new calendar.

3.  In the **Calendar type** field, select **5 days**, **6 days**, **7 days** or **Others** as the calendar type.

4.  In the **Calendar** and **Name** fields, enter a code and a name for the calendar.

5.  In the **Template** field, select the template for the calendar. You can create the calendar based on the template that you create in the **Standard templates** or **Periodic templates** form.
    

    > [!NOTE]
    > <P>Standard templates can be created for one week. Periodic templates can be created for a specific period. You can specify the period intervals based on the number of days. For example, if you want to create a template for three weeks, then the period interval is 21.</P>



6.  Select the **Holiday accounting** check box to create a calendar that includes the holidays from the list of public holidays.

7.  In the **Number of work hours** field, enter the number of working hours in a day.

8.  To create and update daily records for the current calendar, click **Calendar**.

9.  To change the daily records for the current calendar, in the **Calendar** form, click **Creating calendar** to open the **Creating calendar** form.

10. In the **From date** and **To date** fields, enter the starting date and ending date for the calendar. The template for the calendar displays automatically in the **Template** field.

11. Click **OK** to create daily records in the calendar.

## Copy schedule from one calendar to another calendar

You can copy the schedule from one calendar to another calendar, and view the number of working days and hours for the calendar in the **Calendars setup** form.

1.  Click **Payroll (Russia)** \> **Working time registration** \> **Calendar** \> **Calendars setup**.

2.  To open the **Copy calendar** form, click **Copy**.

3.  In the **From calendar** and **To calendar** fields, select the calendar period that is to be copied.

4.  On the **Times** tab, you can view the number of working days and hours for the calendar, sorted by month and time code.

5.  On the **Groups** tab, you can view the number of working days and hours for the calendar, sorted by month and time group.

## Next step

[(RUS) Create a timesheet for an employee](rus-create-a-timesheet-for-an-employee.md)

## Related tasks

[(RUS) Hire, transfer, and dismiss a worker](rus-hire-transfer-and-dismiss-a-worker.md)

[(RUS) Support the workforce management process](rus-support-the-workforce-management-process.md)

[(RUS) Set up parameters for the payroll process](rus-set-up-parameters-for-the-payroll-process.md)

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
<li><p><strong>Human resources administrator</strong></p></li>
</ul>
<p>To configure parameters for time management, you must be a member of a security role that includes the following duties.</p>
<ul>
<li><p><strong>Set up time management master data</strong> (RPaySetupTimeMasterData)</p></li>
<li><p><strong>Inquire into time management master data</strong> (RPayTimeMasterDataInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To configure parameters for time management, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Maintain time management setting</strong></p></td>
<td><p>RPayTimeMngSettingsMaintain</p></td>
<td><p>Configure general settings for timesheet.</p></td>
</tr>
<tr class="even">
<td><p><strong>View time management settings</strong></p></td>
<td><p>RPayTimeMngSettingsView</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain calendars</strong></p></td>
<td><p>RPayCalendarMaintain</p></td>
<td><p>Create a calendar.</p></td>
</tr>
<tr class="even">
<td><p><strong>View calendars setting</strong></p></td>
<td><p>RPayCalendarSettingsView</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain calendars data</strong></p></td>
<td><p>RpayCalDataMaintain</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Maintain holiday days</strong></p></td>
<td><p>RPayHolidaysMaintain</p></td>
<td><p>Create a list of public holidays.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain time codes</strong></p></td>
<td><p>RPayTeamCodesMaintain</p></td>
<td><p>Create list of time codes.</p></td>
</tr>
<tr class="even">
<td><p><strong>View time codes &amp; groups</strong></p></td>
<td><p>RPayTimeCodeGruopsView</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain work time profile groups</strong></p></td>
<td><p>RPayTeamGroupsMaintain</p></td>
<td><p>Create time groups.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain payroll earnings</strong></p></td>
<td><p>RPayAvgPayrollMaintain</p></td>
<td><p>Create a payment form and assign a list of time codes.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View payment forms setting</strong></p></td>
<td><p>RPayPayFormSettingsView</p></td>
<td></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


