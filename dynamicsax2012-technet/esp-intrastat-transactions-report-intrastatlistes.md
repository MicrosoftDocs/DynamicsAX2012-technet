---
title: (ESP) Intrastat transactions report (IntrastatListES)
TOCTitle: (ESP) Intrastat transactions report (IntrastatListES)
ms:assetid: 2b38fd89-9e43-406d-b6c9-e300e6dbad16
ms:mtpsurl: https://technet.microsoft.com/library/Hh433488(v=AX.60)
ms:contentKeyID: 36941248
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ESP
- Intrastat
- SSRS_Reports.Reports.IntrastatListES
- Intrastat transactions
---

# (ESP) Intrastat transactions report (IntrastatListES) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Intrastat transactions** report displays details of all Intrastat transactions with other European Union (EU) member states. This report is typically used by accounting managers, accountants, and accounting supervisors to inquire into the status of the Intrastat transactions.


> [!NOTE]
> <P>(ESP) This report is available only to legal entities whose primary address is in Spain.</P>



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
<td><p>The date of the shipment batch.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transaction code</strong></p></td>
<td><p>The code for the current transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Commodity</strong></p></td>
<td><p>The item commodity code.</p></td>
</tr>
<tr class="even">
<td><p><strong>Shipment batch</strong></p></td>
<td><p>The shipment batch number of the item transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sequence number</strong></p></td>
<td><p>The continuous number sequence ID of the item transaction in the shipment batch.</p></td>
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
<td><p>IntrastatListES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\IntrastatListES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>IntrastatListES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>Intrastat</strong>. In the <strong>Intrastat</strong> form, click <strong>Output</strong> &gt; <strong>Report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - Intrastat table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


