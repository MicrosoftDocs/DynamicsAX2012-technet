---
title: Expected cash in the next x days chart report (CustExpectedCashNextXDays)
TOCTitle: Expected cash in the next x days chart report (CustExpectedCashNextXDays)
ms:assetid: fb9c7bd6-6aab-4e7e-bb8c-ed6646136de2
ms:mtpsurl: https://technet.microsoft.com/library/Hh538467(v=AX.60)
ms:contentKeyID: 39508898
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustExpectedCashNextXDays
---

# Expected cash in the next x days chart report (CustExpectedCashNextXDays) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view a chart that displays the expected cash receipts for a period of days in the future.

This report is designed for use on Role Centers.

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
<td><p>CustExpectedCashNextXDays</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\CustExpectedCashNextXDays</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustExpectedCashNextXDays</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Credit and Collections Manager and Treasurer Role Centers.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BASEENUM\_FiscalPeriodMonth table

  - BASEENUM\_FiscalQuarter table

  - BICOMPANYVIEW table

  - CustTransOpen table

  - LEDGERPERIODDATEDIMENSIONVIEW table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


