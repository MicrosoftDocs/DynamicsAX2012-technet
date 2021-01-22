---
title: (BEL) PRODCOM report (InventProdCom_BE)
TOCTitle: (BEL) PRODCOM report (InventProdCom_BE)
ms:assetid: 81993367-f156-47c3-b070-990f68fae2be
ms:mtpsurl: https://technet.microsoft.com/library/Hh335158(v=AX.60)
ms:contentKeyID: 36687370
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InventProdCom_BE
- PRODCOM
- PRODCOM report
---

# (BEL) PRODCOM report (InventProdCom\_BE) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **PRODCOM** report displays production statistics for industrial products that are manufactured by production companies operating within Belgium. This report must be submitted monthly to the Nationaal Instituut voor de Statistiek (NIS). This report is typically used by accounting managers and accountants.


> [!NOTE]
> <P>(BEL) This report is available only to legal entities whose primary address is in Belgium.</P>



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
<td><p><strong>Branch number</strong></p></td>
<td><p>Enter the branch ID of the company’s production unit in x.xxx.xxx.xxx format. The production statistics for this branch are included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Preprinted document</strong></p></td>
<td><p>Select this check box if you want to print the production statistics on a preprinted form.</p></td>
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
<td><p>InventProdCom_BE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventProdCom_BE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventProdComReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>PRODCOM</strong>. In the <strong>PRODCOM</strong> form, click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InventProdComTmp\_BE table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the InventProdComDP_BE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


