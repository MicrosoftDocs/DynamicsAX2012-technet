---
title: Course participants report (HcmCourseAttendeeStatusList)
TOCTitle: Course participants report (HcmCourseAttendeeStatusList)
ms:assetid: 688cf2eb-a98c-4c3c-a5ff-24baeb708abc
ms:mtpsurl: https://technet.microsoft.com/library/JJ841460(v=AX.60)
ms:contentKeyID: 50411099
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.HcmCourseAttendeeStatusList
---

# Course participants report (HcmCourseAttendeeStatusList) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print a listing of all people who are registered or confirmed for a course or who are on the waiting list.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>List of participants</strong></p></th>
<th><p><strong>Waiting list</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Print this report for a listing of all registered or confirmed course participants. The results are sorted by course.</p></td>
<td><p>Print this report for a listing of all participants that are currently on the waiting list for a course.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>HcmCourseAttendeeStatusList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmCourseAttendeeStatusList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HRMCourseAttendeeList</p>
<p>HRMCourseWaitingList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Courses</strong> &gt; <strong>List of participants</strong>.</p>
<p>Click <strong>Human resources</strong> &gt; <strong>Common</strong> &gt; <strong>Courses</strong> &gt; <strong>Courses</strong>. Select a course. On the <strong>Action Pane</strong>, click <strong>List of participants</strong>.</p>
<p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Courses</strong> &gt; <strong>Waiting list</strong>.</p>
<p>Click <strong>Human resources</strong> &gt; <strong>Common</strong> &gt; <strong>Courses</strong> &gt; <strong>Courses</strong>. Select a course. On the <strong>Action Pane</strong>, click <strong>Waiting list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable table

  - HRMCourseAttendee table

  - HRMCourseTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


