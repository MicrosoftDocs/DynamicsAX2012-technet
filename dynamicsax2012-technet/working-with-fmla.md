---
title: Working with FMLA
TOCTitle: Working with FMLA
ms:assetid: 6fe117b9-e2f3-4917-8caa-ba6664d38f06
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876707(v=AX.60)
ms:contentKeyID: 63385349
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.HcmWorkerListPage
- Forms.CaseDetail
- family leave
- unpaid leave
- FMLA
- Forms.HcmFMLACaseListPage
- Forms.HcmFMLAEligibility
- Military leave
- Forms.HcmFMLARecalculateHours
- Maternity leave
- Forms.HcmFMLAHoursTracking
audience: Application User
ms.search.region: Global
---

# Working with FMLA 


This topic describes how to track Family and Medical Leave Act (FMLA) eligibility and hours worked to meet federal requirements.

The following illustration shows the process of entering and tracking FMLA for workers. The numbers correspond to the procedures later in this topic.

![FMLA process flow](images/Dn876707.FMLA(AX.60).jpg "FMLA process flow")

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
<td><p>Task</p></td>
<td><p>The human resources manager must do the following tasks to activate FMLA:</p>
<ul>
<li><p>Click <strong>Human resources</strong> &gt; <strong>Setup</strong> &gt; <strong>Parameters</strong> &gt; <strong>Human resources parameters</strong>. Verify that the settings are accurate.</p></li>
<li><p>Click <strong>Organization administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Cases</strong> &gt; <strong>Case category type security</strong>. Verify that the settings are accurate.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Knowledge and experience</p></td>
<td><p>Be familiar with cases and how they work in Microsoft Dynamics AX. For more information, see <a href="cases.md">Cases</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Planning</p></td>
<td><p>Determine whether you will integrate FMLA with Payroll.</p></td>
</tr>
<tr class="even">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</p></td>
</tr>
<tr class="odd">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States.</p></td>
</tr>
</tbody>
</table>


## 1\. Determine worker eligibility

When a worker submits a leave request or inquires about their FMLA eligibility, you can easily determine how many hours they have available.

To determine worker eligibility, follow these steps:

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to determine eligibility for, and then select **Employment** \> **FMLA eligibility**.

3.  In the **Eligibility date** field, enter the expected date when eligibility will begin.

4.  Click **Calculate**. The number of estimated available hours for both standard FMLA and military FMLA is displayed. This number is determined by the number of hours the employee has worked, their length of employment, and whether the worker has taken any leave that reduces their available remaining hours.

## 2\. Create an FMLA case

FMLA uses cases to track eligibility and hours taken. If you are not familiar with cases in Microsoft Dynamics AX, see [Cases](cases.md).


> [!NOTE]
> <P>Before you create an FMLA case, create the employment leave, if you haven’t already done so. This is required for all leaves of absence, regardless of whether the leave qualifies for FMLA. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa588994(v=ax.60)">Leave (form)</A>.</P>



To create an FMLA case, follow these steps:

1.  Click **Human resources \> Common \> Workers \> FMLA cases**.

2.  On the **Action Pane**, in the **New** group, click **Case**.

3.  Optional: If the case has already been approved, select the **Approved** check box on the **General** tab. You can also select the approver, if applicable.

4.  Enter the following information.
    
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
    <td><p><strong>Reason</strong></p></td>
    <td><p>Select the reason for the leave.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Leave request date</strong></p></td>
    <td><p>Select the date when the leave was requested. This is often today’s date.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Leave start date</strong></p></td>
    <td><p>Select the first day of the leave. If this changes, you can return to this form and update the date.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Estimated leave end date</strong></p></td>
    <td><p>Select the last day that the worker intends to remain on leave. If this changes, you can return to this form and update the date .</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Approved hours</strong></p></td>
    <td><p>Enter the approved hours for the leave. The Eligibility section on the form should help you determine this number.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Leave schedule</strong></p></td>
    <td><p>Select the leave schedule.</p></td>
    </tr>
    </tbody>
    </table>


5.  Optional: On the **Certifications** FastTab, enter any certification information to track.

6.  On the **Associated leave** FastTab, click **Add**. Select the employment leave that corresponds to this FMLA case.

7.  Optional: On the **Case log** FastTab, enter any notes about the case that you want to store for reference purposes.

## 3\. If required: Recalculate FMLA eligibility

After you create an FMLA case for a worker, you can recalculate the worker’s eligibility at any time.

To recalculate a worker’s eligibility, follow these steps:

1.  Click **Human resources \> Common \> Workers \> FMLA cases**.

2.  Open the case to recalculate.

3.  Click **Recalculate eligibility**.

4.  Select the fields to update and click **Recalculate**. The information in the FMLA eligibility section is recalculated based on current information, and the appropriate fields values will be updated. You can make any necessary adjustments to the case based on this information.

## 4\. If required: Enter FMLA hours taken

After an FMLA case is approved, you can change and track the number of hours workers apply toward their FMLA leave.

To enter FMLA hours that have been taken, follow these steps:

1.  Click **Human resources \> Common \> Workers \> FMLA cases**.

2.  Open the case to log hours for.

3.  On the **Action Pane**, in the **Maintain** group, click **FMLA hours**.

4.  Click **Add line** and enter the earning date, hours taken, and any applicable notes.
    

    > [!NOTE]
    > <P>The source column is always set to <STRONG>Manual</STRONG> unless FMLA is integrated with Microsoft Dynamics AX and the line was created by the system.</P>



## 5\. If required: Set up Payroll to integrate with FMLA

If you use Payroll, you can use earning codes to automatically track the hours worked that count toward FMLA. When earning lines that contain these codes are released during the approved leave period for a worker, the time counts toward FMLA and is added to the **FMLA hours** form for the FMLA case.


> [!TIP]
> <P>If you use this method of tracking FMLA hours, you can still change the hours manually after they are created.</P>



To integrate Payroll with FMLA, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Open an earning code that, when hours are logged for a worker, reduces the number of FMLA hours available for the worker.

3.  On the **General** tab, select a value in the **Reduce remaining FMLA time** field.
    

    > [!NOTE]
    > <P>You can select this check box only if the <STRONG>Productive</STRONG> check box isn’t selected and the <STRONG>Unit of measure</STRONG> is set to <STRONG>Hours</STRONG>.</P>



4.  Repeat these steps for all earning codes that should reduce the number of available FMLA hours.

## 6\. Optional: Generate the FMLA hours taken report

You can create a report of all workers who have FMLA cases and the hours that have been applied toward each case.

To generate the FMLA leave taken report, follow these steps:

1.  Click **Human resources \> Reports \> Workers \> FMLA leave taken**.

2.  Enter the first and last day of the leave period that you want to view.

3.  Click **OK**.

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
<td><p><strong>Human resource I</strong></p>
<p>If you integrate FMLA with Payroll: <strong>Payroll - USA</strong></p>
<p>When you use Payroll, we highly recommend that you turn off the <strong>Payroll information</strong> configuration key under the <strong>Human resource I</strong> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p><strong>FMLA administrator</strong></p></td>
</tr>
</tbody>
</table>

  


