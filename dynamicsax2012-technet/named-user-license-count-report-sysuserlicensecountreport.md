---
title: Named user license count report (SysUserLicenseCountReport)
TOCTitle: Named user license count report (SysUserLicenseCountReport)
ms:assetid: 8871eaf3-15a2-47a2-b088-f82c3e519a75
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335160(v=AX.60)
ms:contentKeyID: 36687372
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SysUserLicenseCountReport
---

# Named user license count report (SysUserLicenseCountReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report contains information about the users who are assigned to security roles in Microsoft Dynamics AX. The report analyzes the roles and privileges that are assigned to each user and then calculates the number of licenses that are required for each user type.

A batch job runs weekly to generate the data for this report. The information in the report is current as of the date that the batch was last run. To verify when the batch was last run, see the **Batch job history** form.


> [!NOTE]
> <P>For more information about how security roles relate to licensing, see the <A href="http://go.microsoft.com/fwlink/?linkid=228370">Security roles and licensing white paper</A> for Microsoft Dynamics AX 2012.</P>



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
<td><p><strong>Date for Named User License User Count:</strong></p></td>
<td><p>The date for which you want to generate the user license count report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show list of users per access license type (for latest report only)</strong></p></td>
<td><p>Select this option to return a list of aliases and user IDs for each license type. If you select this option, you cannot select a date that is in the past. Historical user data is not retained in the database. If you select a historical date, specific aliases and user IDs will not be listed.</p>
<p>If you do not select this option, the report displays the number of users who are assigned to each license type as of the selected date.</p></td>
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
<td><p>SysUserLicenseCountReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SysUserLicenseCountReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SysUserLicenseCountReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Reports</strong> &gt; <strong>Licensing</strong> &gt; <strong>Named User License Counts</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SysUserLicenseCountTmp


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the SysUserLicenseCountReport.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


