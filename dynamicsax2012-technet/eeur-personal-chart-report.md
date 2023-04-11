---
title: (EEUR) Personal chart (report)
TOCTitle: (EEUR) Personal chart (report)
ms:assetid: 3600a2d1-d841-4b54-a443-f41b5670478b
ms:mtpsurl: https://technet.microsoft.com/library/JJ874406(v=AX.60)
ms:contentKeyID: 50619723
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Personal chart (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a report that displays a selected employee’s personal information.


> [!NOTE]
> <P>In Estonia, an employee can ask to view a report of when and by whom the employee’s personal information was accessed. For more information about how to generate this report, see <A href="est-generate-a-report-of-accessed-personal-information-for-an-employee.md">(EST) Generate a report of accessed personal information for an employee</A>.</P>



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
<td><p><strong>Person</strong></p></td>
<td><p>Select the employee whose personal information is generated and displayed on the report.</p></td>
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
<td><p>EePersonalDataPerUser</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\EePersonalDataPerUser</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>EePersonalDataPerUser</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Personal data</strong> &gt; <strong>Personal chart</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - EePersonalDataPerUserTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


