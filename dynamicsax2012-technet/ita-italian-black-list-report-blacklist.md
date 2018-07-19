---
title: (ITA) Italian black list report (BlackList)
TOCTitle: (ITA) Italian black list report (BlackList)
ms:assetid: 0e12b6a8-5df1-4b89-951b-5890e5e2bb22
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433479(v=AX.60)
ms:contentKeyID: 36941239
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BlackList
---

# (ITA) Italian black list report (BlackList) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Italian black list report** displays and prints a list of taxable transactions with countries that have privileged tax structures. These countries are referred to as “black listed” by the Italian government. This report must be submitted to Italian sales tax authorities in ASCII format. This report is used to maintain and inquire into the status of sales tax transactions. This report is typically used by accountants, collections managers, accounts receivable clerks, accounts receivable managers, sales managers, and sales clerks.

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
<td><p><strong>Generate file</strong></p></td>
<td><p>Select this check box to export the report as an ASCII file.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Select or enter the file name and path where the report is stored.</p></td>
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
<td><p>BlackList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BlackList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BlackListReport_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Italian black list report</strong>. In the <strong>Black list report ID</strong> field, select a report ID, and then click <strong>Report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpBlackListReport\_IT table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the BlackListReportDP_IT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


