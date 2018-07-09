---
title: Customer invoice report (SalesInvoice)
TOCTitle: Customer invoice report (SalesInvoice)
ms:assetid: 347311cf-2989-42c2-a6ec-c29130df2345
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242607(v=AX.60)
ms:contentKeyID: 36057965
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SalesInvoice
---

# Customer invoice report (SalesInvoice) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Customer invoice report** displays customer invoice information. This includes sales order, packing slip, and line details.

## How to filter the data on this report

There are several parameters that can be used to filter the data that is displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

For additional information about how to configure the filters for this report, see [Sales posting (form)](https://technet.microsoft.com/en-us/library/aa550287\(v=ax.60\)).

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
<td><p>SalesInvoice</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SalesInvoice</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SalesInvoice</p>
<p>SalesInvoiceCopy</p>
<p>SalesInvoiceOriginal</p>
<p>ShipCarrierShipmentInvoiceCopy</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Sales orders</strong> &gt; <strong>All sales orders</strong>. On the <strong>Action Pane</strong>, on the <strong>Invoice</strong> tab, in the <strong>Generate</strong> group, click <strong>Invoice</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SalesInvoiceTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the SalesInvoiceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Set up print management for a transaction](set-up-print-management-for-a-transaction.md)

[Print management setup (form)](https://technet.microsoft.com/en-us/library/hh209383\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

