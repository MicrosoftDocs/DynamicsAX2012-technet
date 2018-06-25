---
title: (CAN, USA) Sales analysis by invoice report (CustSalesAnalysisByInvoice_NA)
TOCTitle: (CAN, USA) Sales analysis by invoice report (CustSalesAnalysisByInvoice_NA)
ms:assetid: 148a1fc4-bdc3-4261-a773-aba6501b00fd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh496414(v=AX.60)
ms:contentKeyID: 37071991
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustSalesAnalysisByInvoice_NA
---

# (CAN, USA) Sales analysis by invoice report (CustSalesAnalysisByInvoice\_NA) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Sales analysis by invoice** report displays customer invoice details such as the invoice number, invoice date, invoice amount, and total miscellaneous charges. This report is used to analyze customer invoices. This report is typically used by the chief executive officers, chief financial officers, compliance managers, accounting managers, and financial controllers.


> [!NOTE]
> <P>(CAN, USA) This report is available only to legal entities whose primary address is in Canada or the United States.</P>



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
<td><p><strong>Date</strong></p></td>
<td><p>The date when the sales invoice was posted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice</strong></p></td>
<td><p>The identification of the sales invoice that the report is generated for.</p></td>
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
<td><p>CustSalesAnalysisByInvoice_NA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustSalesAnalysisByInvoice_NA</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustSalesAnalysisByInvoice_NA</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Invoice</strong> &gt; <strong>Sales analysis by invoice</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustInvoiceJour table

  - DirPartyTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

