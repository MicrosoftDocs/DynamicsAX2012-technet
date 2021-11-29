---
title: Letter of credit application report (BankLCImportApplication)
TOCTitle: Letter of credit application report (BankLCImportApplication)
ms:assetid: 03bc3d3f-e7d3-4a23-8059-485f7eef1b33
ms:mtpsurl: https://technet.microsoft.com/library/Hh692455(v=AX.60)
ms:contentKeyID: 41702350
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankLCImportApplication
---

# Letter of credit application report (BankLCImportApplication) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays a letter of credit application.

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
<td><p>BankLCImportApplication</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankLCImportApplication</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankLCImportApplication</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Common</strong> &gt; <strong>Letters of credit</strong> &gt; <strong>Import letter of credit/import collection</strong>. Double-click the order number that is associated with the import letter of credit. On the <strong>Action Pane</strong>, click <strong>Print application</strong>.</p>
<p>–or–</p>
<p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Common</strong> &gt; <strong>Purchase orders</strong> &gt; <strong>All purchase orders</strong>. Select a purchase order. On the <strong>Action Pane</strong>, click the <strong>Manage</strong> tab, and then click <strong>Letter of credit / import collection</strong>. On the <strong>Action Pane</strong>, click <strong>Print application</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankLCImportApplicationDP.processReport class

  - BankLCImportApplicationPurchLineTmp table

  - BankLCImportApplicationShipmentTmp table

  - BankLCImportApplicationTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the BankLCImportApplicationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


