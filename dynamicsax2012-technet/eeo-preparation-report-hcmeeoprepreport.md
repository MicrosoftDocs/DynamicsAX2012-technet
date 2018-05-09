---
title: EEO preparation report (HcmEEOPrepReport)
TOCTitle: EEO preparation report (HcmEEOPrepReport)
ms:assetid: 94bd1532-3b78-44f3-bc80-e9cd7810f9cb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn268418(v=AX.60)
ms:contentKeyID: 54916955
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# EEO preparation report (HcmEEOPrepReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

There are several versions of the EEO preparation report that you can use when you prepare the reports required by the U.S. Equal Employment Opportunity Commission. The EEOC enforces the federal laws that prohibit discrimination against a job applicant or an employee because of the person's race, color, religion, sex (including pregnancy), national origin, age (40 or older), disability, or genetic information.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</P>



The following list includes all of the available versions of the EEO preparation report:

  - **Incomplete EEO-related values**: Used to identify any missing information that would prevent you from completing an EEO report accurately.

  - **EEO-1**: Used by private-sector entities.

  - **EEO-4**: Used by state and local governments.

  - **EEO-5**: Used by public elementary or secondary schools and school districts.

You should always run the **Incomplete EEO-related values** report and enter missing information before you run any of the other EEO preparation reports. The first time that you run this report, it is possible that every worker will be missing the **Classification of the position type**. This field, which is set up in the **Position types** form, indicates whether the position is full-time or part-time.

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
<td><p><strong>As of</strong></p></td>
<td><p>Each EEO report includes the workers who have an active employment on this date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Regulatory establishment</strong></p></td>
<td><p>The work location that you are completing the report for.</p></td>
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
<td><p>HcmEEOPrepReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmEEOPrepReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HcmEEOPrepReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Workers</strong> &gt; <strong>Regulatory</strong> &gt; <strong>EEO preparation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HcmWorker

  - HcmEmployment

  - HcmPositionWorkerAssignment

  - HcmPersonPrivateDetails

  - HcmPositionDetail

  - HcmJob

  - HcmJobDetail

  - HcmJobFunction

  - HcmEthnicOrigin

  - HcmPositionType

  - DirPerson

  - HrmCompFixedEmpl

These tables are all included in the query HcmEEOPrepReport.

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

