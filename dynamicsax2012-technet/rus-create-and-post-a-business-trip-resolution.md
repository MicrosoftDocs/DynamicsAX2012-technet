---
title: (RUS) Create and post a business trip resolution
TOCTitle: (RUS) Create and post a business trip resolution
ms:assetid: d2f97f7e-c100-401e-99b1-7b51530f0397
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn457781(v=AX.60)
ms:contentKeyID: 58984546
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RHRMOrderTable
- Forms.RHRMOrderTrans
- business trip
- business trip resolution
- MsDynAx060.Forms.RHRMOrderTable
- MsDynAx060.Forms.RHRMOrderTrans
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post a business trip resolution 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create and post a business trip resolution. To assign an employee to a business trip, you must create and confirm a business trip resolution in the **Business trip resolutions** form. This business trip resolution is used by the payroll department to pay the employee for the business trip.

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
<li><p>Create business trip codes. For more information, see <a href="rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md">(RUS) Set up vacations, business trips, and incentives for the payroll process</a>.</p></li>
<li><p>Create a calendar that can be used as a work schedule for employees. For more information, see &quot;Create a calendar&quot; in <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
<li><p>Assign time codes for business trips. For more information, see &quot;Assign time codes to a special time account&quot; in <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
<li><p>Create calculation sequences for business trip payments. For more information, see &quot;Set up a business trip calculation method&quot; in <a href="rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md">(RUS) Set up vacations, business trips, and incentives for the payroll process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Create a business trip resolution

To create a business trip resolution, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Business trips**.

2.  Click **New** to create a new business trip resolution journal.

3.  On the **Overview** tab, specify the following details.
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>Select the journal name.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The journal number is generated and displayed in the <STRONG>Journal</STRONG> field based on the number sequence code that you define for the journal in the <STRONG>Staff administration parameters</STRONG> form.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Resolution date</strong></p></td>
    <td><p>Select the resolution creation date.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The resolution number is generated and displayed in the <STRONG>Resolution number</STRONG> field based on the number sequence code that you define for the business trip resolution in the <STRONG>Staff administration parameters</STRONG> form.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Organization</strong></p></td>
    <td><p>The destination organization for the business trip.</p></td>
    </tr>
    </tbody>
    </table>


4.  On the **Location** tab, enter the destination address details.

5.  Click **Lines** to open the **Business trip resolutions lines** form.

6.  Click **New** to create a new business trip resolution line.

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
    <td><p>Select an employee code. The name of the employee displays automatically in the <strong>Employee name</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Business trip type</strong></p></td>
    <td><p>Select the type of business trip.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Start date</strong></p></td>
    <td><p>Select the starting date of the business trip.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>End date</strong></p></td>
    <td><p>Select the ending date of the business trip.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The business trip duration displays automatically in the <STRONG>Period</STRONG> field based on the start date and the end date.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Period</strong></p></td>
    <td><p>Select the duration of the business trip.</p>
    <div class="alert">

    > [!NOTE]
    > <P>When you modify the period in the <STRONG>Period</STRONG> field, the end date displays automatically in the <STRONG>End date</STRONG> field based on the start date.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


8.  On the **General** tab, in the **Purpose** field, enter the purpose of the business trip.

9.  In the **At the cost of** field, enter the name of the party or organization that is funding the business trip.

10. Click **Validate** to validate the resolution lines, and then click **OK** in the **Check journal** form.

11. Click **Post** to post the journal, and then click **OK** in the **Post journal** form.
    

    > [!NOTE]
    > <P>The <STRONG>Posted</STRONG> check box is selected automatically in the <STRONG>Business trip resolutions</STRONG> form.</P>



## 2\. Cancel or correct a business trip resolution

You can cancel the journal posting when you need to update the business trip resolution or correct a mistake in the business trip resolution.

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Business trips**.

2.  In the **Business trip resolutions** form, select the business trip resolution to cancel.

3.  Click **Restore** to cancel the journal posting in the **Post journal** form.

4.  Click **OK** to cancel the selected business trip resolution. You must cancel the related payments of the resolution journal, and then cancel the journal posting.

## 3\. Print business trip resolution reports

You can generate and print the business trip resolution reports. For more information, see [(RUS) Vacation, business trip, and sick list reports](rus-vacation-business-trip-and-sick-list-reports.md).

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Business trips**.

2.  Click **Print** \> **Form T-9a** to print a report that displays the business trip details of all employees in the HR department business trip resolution form (statutory Form T-9a) for individuals.

3.  Click **Lines** to open the **Business trip resolutions lines** form.

4.  Click **Print** \> **Form T-10** to print a business trip certificate (statutory Form T-10) that displays planned business trip details of an employee.

5.  Click **Print** \> **Form T-10a** to print business trip certificates (statutory Form T-10a) that display the planned business trip details of all employees.

6.  Click **Print** \> **Form T-9** to print a report that displays the business trip details of an employee in the HR department business trip resolution form (statutory Form T-9) for an individual.

## 4\. View an employee’s business trip information

You can view the posted business trip resolution lines for an employee in the **Employees** form.

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  On the **Employment** tab, click **Business trips** to view the posted business trip resolution for the selected employee.

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
<p>To create a business trip resolution, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create a business trip resolution, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Maintain business trips resolution</strong></p></td>
<td><p>RPayBTResolutionMaintain</p></td>
<td><p>Create a business trip resolution.</p></td>
</tr>
<tr class="even">
<td><p><strong>View business trips resolution</strong></p></td>
<td><p>RPayBTResolutionView</p></td>
<td></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


