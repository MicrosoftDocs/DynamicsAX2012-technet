---
title: (USA) Tax 1099 detail report (Tax1099Detail)
TOCTitle: (USA) Tax 1099 detail report (Tax1099Detail)
ms:assetid: ac1cdb03-ab69-4389-8d7d-30d892c39be4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa618342(v=AX.60)
ms:contentKeyID: 36941297
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.Tax1099Detail
---

# (USA) Tax 1099 detail report (Tax1099Detail) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Tax 1099 detail** report is used to print a detailed list of 1099 statement transactions for each vendor and to verify the information before filing 1099 statements with the IRS. The report shows the 1099 amount for each voucher, the vendor's total amount by box, the vendor's total 1099 amount, and a total of the 1099 amounts for all vendors specified on the report. This report is typically used by collections managers, accountants, accounting managers, and accounting supervisors.


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
<td><p><strong>Vendor account</strong></p></td>
<td><p>The identification number of the vendor account for which the report is generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>State</strong></p></td>
<td><p>The state where the 1099 statements are filed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>1099 box</strong></p></td>
<td><p>The box code on the 1099 form where the total amount is posted.</p></td>
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
<td><p>Tax1099Detail</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\Tax1099Detail</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Tax1099Detail</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Tax 1099</strong> &gt; <strong>Tax 1099 detail</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - Tax1099Detail table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(USA) About year-end 1099 reporting](usa-about-year-end-1099-reporting.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

