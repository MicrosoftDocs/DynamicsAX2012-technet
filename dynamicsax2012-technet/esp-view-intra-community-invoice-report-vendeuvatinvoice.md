---
title: (ESP) View Intra-Community invoice report (VendEUVatInvoice)
TOCTitle: (ESP) View Intra-Community invoice report (VendEUVatInvoice)
ms:assetid: d36e4116-c796-4c9e-96e1-1982f370c7af
ms:mtpsurl: https://technet.microsoft.com/library/Hh496454(v=AX.60)
ms:contentKeyID: 37072037
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendEUVatInvoice
---

# (ESP) View Intra-Community invoice report (VendEUVatInvoice) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **View Intra-Community invoice** report displays and prints a copy of the intra-community invoice. The intra-community invoice is issued for transactions between legal entities that are located in different European Union (EU) member states. This report is typically used by accountants, accounting managers, purchase managers, financial controllers, and clerks to review the status of purchase orders and to inquire into the status of vendor invoices.

Before you view this report, you must select the **EU sales tax for Spanish invoices** check box on the **Sales tax** FastTab in the **Ledger and sales tax** link in the **Accounts payable parameters** form.


> [!NOTE]
> <P>(ESP) This report is available only to legal entities whose primary address is in Spain.</P>



## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

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
<td><p>VendEUVatInvoice</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendEUVatInvoice</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendEUVatInvoice</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Journals</strong> &gt; <strong>Invoice journal</strong>. Select a transaction, and then click <strong>View Intra-Community invoice</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendEUVatInvoiceTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendEUVatInvoiceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


