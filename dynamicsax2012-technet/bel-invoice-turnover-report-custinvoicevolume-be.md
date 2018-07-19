---
title: (BEL) Invoice turnover report (CustInvoiceVolume_BE)
TOCTitle: (BEL) Invoice turnover report (CustInvoiceVolume_BE)
ms:assetid: ef3bf281-c87a-4c6b-a83f-74f5610519e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335172(v=AX.60)
ms:contentKeyID: 36687388
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustInvoiceVolume_BE
- (BEL)
- Invoice turnover
- Invoice turnover report
---

# (BEL) Invoice turnover report (CustInvoiceVolume\_BE) 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Invoice turnover report displays customer invoice turnover information for a specified period. The report is based on the minimum amount criterion. An XML file that contains the invoice turnover details can also be generated. This report is used by accounts receivable managers and accounting managers to review the performance of invoice and cash processes.

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
<td><p><strong>From date</strong></p></td>
<td><p>Enter the starting date of the period that the report is generated for.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the period that the report is generated for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Minimum amount</strong></p></td>
<td><p>Enter the minimum turnover amount that is included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Official declaration</strong></p></td>
<td><p>Select this check box to print the invoice turnover details for submission as an official declaration record.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Create XML file</strong></p></td>
<td><p>Select this check box to create an XML file that contains the invoice turnover details.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file path and file name for the XML file.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Replaced Invoice turnover declaration</strong></p></td>
<td><p>Enter the identification number of the previously submitted declaration that is replaced.</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The country/region of the customer.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Country/region type</strong></p></td>
<td><p>The identification code of the country or region type of the customer. For example, if the customer organization is in the Netherlands, the country/region type is <strong>EU</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Enterprise number</strong></p></td>
<td><p>The enterprise number that is used to identify Belgian companies.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer account</strong></p></td>
<td><p>The customer account number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tax exempt number</strong></p></td>
<td><p>The tax exempt number of the customer.</p></td>
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
<td><p>CustInvoiceVolume_BE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustInvoiceVolume_BE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustInvoiceVolume_BE</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Sales tax payments</strong> &gt; <strong>Belgium</strong> &gt; <strong>Invoice turnover</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - CustInvoiceVolumeTmp\_BE table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for CustInvoiceVolumeDP_BE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(BEL) Create an INTERVAT declaration file](bel-create-an-intervat-declaration-file.md)

  


