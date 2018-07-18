---
title: Course agenda report (HcmCourseAgenda)
TOCTitle: Course agenda report (HcmCourseAgenda)
ms:assetid: 53b15a7b-f208-4c2b-99f5-30e6106a82e8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ841459(v=AX.60)
ms:contentKeyID: 50411098
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.HcmCourseAgenda
---

# Course agenda report (HcmCourseAgenda) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print an overview of course agendas. This report includes only courses with a setup of **Agenda** or **Agenda + session**.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

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
<td><p><strong>Print sessions</strong></p></td>
<td><p>Select this check box to include the course sessions and tracks in the report results.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print instructors</strong></p></td>
<td><p>Select this check box to include the course instructors in the report results.</p></td>
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
<td><p>HcmCourseAgenda</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmCourseAgenda</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HRMCourseAgenda</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Courses</strong> &gt; <strong>Setup lists</strong> &gt; <strong>Course agenda</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HcmCourseAgendaTmp table

  - HRMCourseAgenda table

  - HCMCourseTable table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the HcmCourseAgendaDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


