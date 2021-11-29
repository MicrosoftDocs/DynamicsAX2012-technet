---
title: (ISL) Vendor invoice declaration report (VendOutInvoiceSumByDeclaration_IS)
TOCTitle: (ISL) Vendor invoice declaration report (VendOutInvoiceSumByDeclaration_IS)
ms:assetid: 7cf254c5-b11d-4d87-a2c5-f29b522e01e7
ms:mtpsurl: https://technet.microsoft.com/library/Hh433503(v=AX.60)
ms:contentKeyID: 36941275
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendOutInvoiceSumByDeclaration_IS
---

# (ISL) Vendor invoice declaration report (VendOutInvoiceSumByDeclaration\_IS) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Vendor invoice declaration** report displays the details of payments that are made to vendors, together with invoice totals for each reporting code. This report is used by accounts payable clerks, accounts payable managers, buying agents, project managers, and purchasing managers to inquire into the status of purchase orders that are invoiced. This report must be submitted as a text file to the Icelandic tax authorities as a yearly declaration report.


> [!NOTE]
> <P>(ISL) This report is available only to legal entities whose primary address is in Iceland.</P>



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
<td><p><strong>Authority</strong></p></td>
<td><p>Select the number of the sales tax authority.</p></td>
</tr>
<tr class="even">
<td><p><strong>Currency code</strong></p></td>
<td><p>Select the currency code that is used to post the vendor transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date of the period for which the report is generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the period for which the report is generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Create text file</strong></p></td>
<td><p>Select this check box to create the vendor declaration report as a text file. This file is submitted to the Icelandic tax authorities.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Select or enter a file name and file path where the report is saved.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show negative amounts in report</strong></p></td>
<td><p>Select this check box to show the negative payment amounts in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show negative amounts in file</strong></p></td>
<td><p>Select this check box to show negative payment amounts in the text file.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice account</strong></p></td>
<td><p>The vendor account that is used to generate the invoice.</p></td>
</tr>
<tr class="even">
<td><p><strong>Purchase order</strong></p></td>
<td><p>The purchase order number that the invoice is attached to.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice</strong></p></td>
<td><p>The identification of the invoice.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor account</strong></p></td>
<td><p>The number of the vendor account.</p></td>
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
<td><p>VendOutInvoiceSumByDeclaration_IS</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutInvoiceSumByDeclaration_IS</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendInvoiceSumByDeclaration_IS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Vendor</strong> &gt; <strong>Vendor invoice declaration</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendInvoiceDeclarationTmp\_IS table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendOutInvoiceSumByDeclarationDP_IS.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


