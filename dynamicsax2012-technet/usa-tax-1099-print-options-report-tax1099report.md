---
title: (USA) Tax 1099 print options report (Tax1099Report)
TOCTitle: (USA) Tax 1099 print options report (Tax1099Report)
ms:assetid: 386de0c0-cf81-456b-b286-ebffbbfafd80
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa553655(v=AX.60)
ms:contentKeyID: 36941249
ms.date: 06/29/2016
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.Tax1099Report
---

# (USA) Tax 1099 print options report (Tax1099Report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Tax 1099 print options** report is used to print 1099 statements. You must select the type of tax 1099 form, indicate the reporting year, and make other selections, such as vendor or state. This report is typically used by collections managers, accountants, accounting managers, and accounting supervisors.


> [!NOTE]
> <P>(USA) This report is only available to legal entities whose primary address is in the United States.</P>



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
<td><p><strong>Type of Tax 1099 form</strong></p></td>
<td><p>Select the type of tax form to print.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reporting year</strong></p></td>
<td><p>Enter the reporting year for the 1099 statements.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Assign unique numbers for 1099 statements.</strong></p></td>
<td><p>Select this check box to assign unique numbers to the 1099 statements. If the check box is not selected, numbers are generated automatically based on the setup in the <strong>Company information</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>State</strong></p></td>
<td><p>Select the state where the 1099 statements are filed.</p></td>
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
<td><p>Tax1099Report</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\Tax1099Report</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Tax1099Report</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Periodic</strong> &gt; <strong>Vendor settlement for 1099s</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - Tax1099IRSPayerRec table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the Tax1099ReportDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(USA) About year-end 1099 reporting](usa-about-year-end-1099-reporting.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

