---
title: (CZE) Vendor advance invoices journal report (VendAdvanceInvoiceJour)
TOCTitle: (CZE) Vendor advance invoices journal report (VendAdvanceInvoiceJour)
ms:assetid: f82747c7-39be-4727-9f67-25da4221dfaf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn133214(v=AX.60)
ms:contentKeyID: 53365032
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- prepayment
- vendor advance
- prepay
- SSRS_Reports.Reports.VendAdvanceInvoiceJour
---

# (CZE) Vendor advance invoices journal report (VendAdvanceInvoiceJour) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX, you can make a payment to a vendor in advance of receiving items and services from the vendor. To track this prepayment, you can create an advance invoice for the vendor. When the items and services are delivered, you can apply the prepayment to the amount due to the vendor for the purchase.

The **Advance invoices journal** report displays vendor advance invoice transactions. The transactions are sorted in the order of vendor account numbers, and then by invoice date. You can filter the report to display a specific vendor account, invoice date, invoice number, and invoice currency, or any combination of these criteria.

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
<td><p><strong>Currency</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>VendAdvanceInvoiceJour</strong> form, in the <strong>Criteria</strong> field, select a currency to include on the report. To select more than one currency, click <strong>Add</strong>, and then enter the criteria in the row just added.</p>
<div class="alert">

> [!NOTE]
> <P>If you do not select a currency, all currencies used by all vendors are included on the report.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Invoice account</strong></p></td>
<td><p>Optionally, search for advance invoices for a specific vendor account.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>Optionally, search for advance invoices that were posted on a specific date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Advance invoice</strong></p></td>
<td><p>Optionally, search for a specific advance invoice number.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Variable symbol</strong></p></td>
<td><p>Optionally, search for a specific vendor’s invoice number.</p></td>
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
<td><p>VendAdvanceInvoiceJour</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendAdvanceInvoiceJour</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendAdvanceInvoiceJour</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Invoice</strong> &gt; <strong>Advance invoices journal</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendAdvanceInvoiceJourDP.processReport

  - VendAdvanceInvoiceJourTmp

  - CzVendAdvanceInvoiceTable


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the VendAdvanceInvoiceJourDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


