---
title: Treasurer liabilities analysis report (TreasurerLiabilitiesAnalysis)
TOCTitle: Treasurer liabilities analysis report (TreasurerLiabilitiesAnalysis)
ms:assetid: fd3d3b6a-8d7c-4799-afb2-5c2786225488
ms:mtpsurl: https://technet.microsoft.com/library/Hh556875(v=AX.60)
ms:contentKeyID: 39509610
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TreasurerLiabilitiesAnalysis
---

# Treasurer liabilities analysis report (TreasurerLiabilitiesAnalysis) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays liability information for a treasurer.

## Details of this report

This report is designed for use on Role Centers.

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
<td><p>TreasurerLiabilitiesAnalysis</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\TreasurerLiabilitiesAnalysis</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TreasurerLiabilitiesAnalysis</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Treasurer Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BASEENUM\_FiscalQuarter table

  - BICOMPANYVIEW table

  - LEDGERPERIODDATEDIMENSIONVIEW table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


