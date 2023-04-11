---
title: (AUS) Fixed asset - low value pool statement report (AssetStatementLowValuePool_AU)
TOCTitle: (AUS) Fixed asset - low value pool statement report (AssetStatementLowValuePool_AU)
ms:assetid: 0cd81043-4bfd-4e46-bffb-b3f55d2376eb
ms:mtpsurl: https://technet.microsoft.com/library/Hh352233(v=AX.60)
ms:contentKeyID: 36687859
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- Fixed asset
- SSRS_Reports.Reports.AssetStatementLowValuePool_AU
- statement
- (AUS)
- AssetStatementLowValuePool_AU
- Low value
- pool statement
---

# (AUS) Fixed asset - low value pool statement report (AssetStatementLowValuePool\_AU) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Fixed asset - low value pool statement** report is used to display the transaction status of low value pool fixed assets. This report is typically used by financial controllers, accountants, accounting managers, and accounting supervisors.


> [!NOTE]
> <P>(AUS) This report is available only to legal entities whose primary address is in Australia.</P>



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
<td><p><strong>Start date</strong></p></td>
<td><p>Enter the starting date of the fiscal year or the starting date of the time period for which the report is to be generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>End date</strong></p></td>
<td><p>Enter a date within the fiscal year or the ending date of the time period for which the report is to be generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Row name</strong></p></td>
<td><p>The name of the fixed asset statement row.</p></td>
</tr>
<tr class="even">
<td><p><strong>Value model</strong></p></td>
<td><p>The identification of the value model that is used to post the transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Posting layer</strong></p></td>
<td><p>The layer to which a transaction is posted. The posting layer can be current, operating, or fiscal.</p></td>
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
<td><p>AssetStatementLowValuePool_AU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ AssetStatementLowValuePool_AU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetStatementLowValuePool</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Fixed asset - low value pool statement</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - AssetStatementLowValuePoolTmp\_AU table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the AssetStatementLowValuePoolDP_AU.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


