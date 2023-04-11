---
title: Chief financial officer long-term solvency report (CFOLongTermSolvency)
TOCTitle: Chief financial officer long-term solvency report (CFOLongTermSolvency)
ms:assetid: 5d90d7d4-88a6-47a9-8f5f-5a239d5aeabb
ms:mtpsurl: https://technet.microsoft.com/library/Hh692464(v=AX.60)
ms:contentKeyID: 41702360
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CFOLongTermSolvency
---

# Chief financial officer long-term solvency report (CFOLongTermSolvency) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays long-term liquidity information for a chief financial officer.


> [!NOTE]
> <P>This report is designed for use on Role Centers.</P>



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
<td><p>ControllerLongTermSolvency</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ControllerLongTermSolvency</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerControllerLongTermSolvencySmall</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Chief Financial Officer Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BICOMPANYVIEW table

  - LEDGERPERIODDATEDIMENSIONVIEW table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


