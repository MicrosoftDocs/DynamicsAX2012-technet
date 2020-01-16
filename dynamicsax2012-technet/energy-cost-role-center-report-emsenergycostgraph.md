---
title: Energy cost Role Center report (EMSEnergyCostGraph)
TOCTitle: Energy cost Role Center report (EMSEnergyCostGraph)
ms:assetid: ed7b4006-e6ed-4ea2-ab29-91b05b673834
ms:mtpsurl: https://technet.microsoft.com/library/Hh404051(v=AX.60)
ms:contentKeyID: 36956718
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.EMSEnergyCostGraph
---

# Energy cost Role Center report (EMSEnergyCostGraph) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the cost of all energy sources. The sources are grouped by category.


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
<td><p>EMSEnergyCostGraph</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\EMSEnergyCostGraph</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>EMSEnergyCostGraph</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Environmental manager Role Centers.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP

  - BIDATEDIM\_DATE

  - EMSSUBSTANCE

  - EMSSUBSTANCECATEGORY

  - EMSDAILYFLOWVIEW

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


