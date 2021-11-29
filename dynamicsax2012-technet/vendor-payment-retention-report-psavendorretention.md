---
title: Vendor payment retention report (PSAVendorRetention)
TOCTitle: Vendor payment retention report (PSAVendorRetention)
ms:assetid: 98847e5e-8471-4388-983c-9abb4113ddae
ms:mtpsurl: https://technet.microsoft.com/library/Hh334497(v=AX.60)
ms:contentKeyID: 36676485
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reports
- project add-in
- SSRS_Reports.Reports.PSAVendorRetention
- payment retention
- vendor payment retention
- retention amount details
- vendor payment reports
- retention amounts
- retention reports
- vendor invoice retention
- vendor payment retention reports
---

# Vendor payment retention report (PSAVendorRetention) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Vendor payment retention** report to view a summary of all vendor payment retention amounts by vendor or by project.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

In the **Assessment** field, select whether you want to organize the report information by vendor or by project. The combination of filters that you select determines what is displayed on the report. For example, if you select **Vendor**, the payment retention totals by vendor are displayed. If there are no vendor payment retention amounts that meet the selection criteria that you entered, the report is empty.

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
<td><p><strong>Include project types</strong></p></td>
<td><p>Select the check boxes for the project types to include on the report. If you do not select any of the check boxes, all project types are included.</p>
<ul>
<li><p><strong>Time and material</strong></p></li>
<li><p><strong>Fixed-price</strong></p></li>
<li><p><strong>Investment</strong></p></li>
<li><p><strong>Cost project</strong></p></li>
<li><p><strong>Internal</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Assessment</strong></p></td>
<td><p>Select whether you want to organize the report by vendor or by project.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor</strong></p></td>
<td><p>Select a vendor to view retention amounts for a specific vendor. You can select a vendor only if you have chosen to organize the report by vendor.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project</strong></p></td>
<td><p>Select a project to view retention amounts for a specific project. You can select a project only if you have chosen to organize the report by project.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the starting date of the date range for which to view retention amounts.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the date range.</p></td>
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
<td><p>PSAVendorRetention</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PSAVendorRetention</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Vendor payment retention</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Retention</strong> &gt; <strong>Vendor payment retention</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PSAVendorRetentionDP.processReport

  - PSAVendorRetentionTmp table
    

    > [!NOTE]
    > <P>To determine where the data in the temp table comes from, view the cross-references for the RFQSendDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Vendor invoices with retention (form)](https://technet.microsoft.com/library/hh209594\(v=ax.60\))

  


