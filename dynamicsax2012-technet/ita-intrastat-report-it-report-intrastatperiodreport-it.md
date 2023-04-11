---
title: (ITA) Intrastat report IT report (IntrastatPeriodReport_IT)
TOCTitle: (ITA) Intrastat report IT report (IntrastatPeriodReport_IT)
ms:assetid: 449a2aa8-5138-4113-83fb-c68bf3d9aa30
ms:mtpsurl: https://technet.microsoft.com/library/Hh352248(v=AX.60)
ms:contentKeyID: 36687874
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- IT
- report
- Intrastat
- SSRS_Reports.Reports.IntrastatPeriodReport_IT
---

# (ITA) Intrastat report IT report (IntrastatPeriodReport\_IT) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Intrastat report IT** report displays Intrastat transaction information about items that are traded among European Union (EU) member states. This report provides transaction information details for arrivals and dispatches for a specific period. This report is used to inquire into the status of Intrastat transactions and is typically used by account managers and accountants.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p>Select or enter the starting date of the reporting period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select or enter the ending date of the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Direction</strong></p></td>
<td><p>Select the direction of the item transactions from the following options:</p>
<ul>
<li><p><strong>Arrivals</strong> – Include transaction information only for acquisitions or arrivals from member states.</p></li>
<li><p><strong>Dispatches</strong> – Include transaction information only for supplies or dispatches to member states.</p></li>
</ul></td>
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
<td><p>IntrastatPeriodReport_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\IntrastatPeriodReport_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>IntrastatPeriodReport_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>Intrastat</strong>. In the <strong>Intrastat</strong> form, click <strong>Output</strong> &gt; <strong>Intrastat report IT</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - IntrastatPeriodReportTmp\_IT table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the IntrastatPeriodReportDP_IT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


