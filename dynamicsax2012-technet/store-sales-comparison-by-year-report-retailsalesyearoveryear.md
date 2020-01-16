---
title: Store sales comparison by year report (RetailSalesYearOverYear)
TOCTitle: Store sales comparison by year report (RetailSalesYearOverYear)
ms:assetid: b430ac06-19f5-413a-bf75-635a34c8598e
ms:mtpsurl: https://technet.microsoft.com/library/Hh697694(v=AX.60)
ms:contentKeyID: 42518522
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Store sales comparison by year report (RetailSalesYearOverYear) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use this report to view the year-over-year sales comparison for a given store. You select the year against which to compare the sales, and the report compares sales for the specified year with the previous year for a given store.


> [!NOTE]
> <P>This report is designed to use in Enterprise Portal for Microsoft Dynamics AX.</P>This report can also be accessed from the Store Manager Role Center.



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
<td><p>RetailSalesYearOnYear</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailSalesYearOnYear</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailSalesYearOnYear</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is not available in the Microsoft Dynamics AX client. However, this report is available in Enterprise Portal.</p>
Click the <strong>Retail</strong> tab, and select the <strong>Sales comparison by year</strong> report. In the <strong>Fiscal year</strong> field, select the fiscal year to which to compare the current year’s sales, and then click <strong>View report</strong>.
<p>This report is also available on the Store Manager Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BIDATEDIM\_DATE table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


