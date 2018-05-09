---
title: Letter of credit details report (BankLCExportDetails)
TOCTitle: Letter of credit details report (BankLCExportDetails)
ms:assetid: 1781abb1-60f4-4d9c-9890-4e0d5f13198b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh692457(v=AX.60)
ms:contentKeyID: 41702352
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankLCExportDetails
---

# Letter of credit details report (BankLCExportDetails) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays a letter of credit for a sales order.

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
<td><p>BankLCExportDetails</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankLCExportDetails</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankLCExportDetails</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Common</strong> &gt; <strong>Sales orders</strong> &gt; <strong>All sales orders</strong>. Select a sales order. On the <strong>Action Pane</strong>, click the <strong>Manage</strong> tab, and then click <strong>Letter of credit</strong>. On the <strong>Action Pane</strong>, click <strong>Print details</strong>.</p>
<p>–or–</p>
<p>Click <strong>Cash and bank management</strong> &gt; <strong>Common</strong> &gt; <strong>Letters of credit</strong> &gt; <strong>Export letter of credit/import collection</strong>. Double-click a letter of credit. On the <strong>Action Pane</strong>, click <strong>Print details</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankLCExportDetailsDP.processReport class

  - BankLCExportDetailsSalesLineTmp table

  - BankLCExportDetailsShipmentTmp table

  - BankLCExportDetailsTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the BankLCExportDetailsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

