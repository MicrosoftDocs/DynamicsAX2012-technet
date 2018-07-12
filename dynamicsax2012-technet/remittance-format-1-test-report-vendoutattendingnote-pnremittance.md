---
title: Remittance format 1 (test) report (VendOutAttendingNote_PNRemittance)
TOCTitle: Remittance format 1 (test) report (VendOutAttendingNote_PNRemittance)
ms:assetid: ef21af79-51af-49d6-bae8-22782c0339fc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527788(v=AX.60)
ms:contentKeyID: 37832041
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendOutAttendingNote_PNRemittance
---

# Remittance format 1 (test) report (VendOutAttendingNote\_PNRemittance) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Remittance format (1) test** report to inquire about status of promissory notes. This report is typically used by chief financial officers, financial controllers, accountants, accounting managers, accounting supervisors, and clerks.

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
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file name and the path where the report details are exported.</p></td>
</tr>
<tr class="even">
<td><p><strong>Attending note</strong></p></td>
<td><p>Select this check box to print an attending note for the report.</p></td>
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
<td><p>VendOutAttendingNote_PNRemittance</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutAttendingNote_PNRemittance</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendOutAttendingNote_PNRemittance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Remittance journal</strong>. Select a journal, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate remittance</strong>. In the <strong>Generate remittance</strong> form, in the <strong>Remittance format</strong> field, select <strong>Remittance format (1) test</strong>. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendOutAttendingNote\_PNRemittanceTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the VendOutAttendingNote_PNRemittanceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


