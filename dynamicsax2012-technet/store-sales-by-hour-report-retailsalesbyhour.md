---
title: Store sales by hour report (RetailSalesByHour)
TOCTitle: Store sales by hour report (RetailSalesByHour)
ms:assetid: 262bbb8f-8a30-4aec-8731-a084c67f6998
ms:mtpsurl: https://technet.microsoft.com/library/Hh697605(v=AX.60)
ms:contentKeyID: 42518406
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Store sales by hour report (RetailSalesByHour) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use this report to and monitor hourly sales volume for a given date. Data on this report can be used by the store manager to staff the store based on peak sales times.


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
<td><p>RetailSalesByHour</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailSalesByHour</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailSalesByHour</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is not available in the Microsoft Dynamics AX client. However, this report is available in Enterprise Portal.</p>
Click the <strong>Retail</strong> tab, and select the <strong>Sales by hour</strong> report. In the <strong>Date</strong> field, select a date, and then click <strong>View report</strong>.
<p>This report is also available on the Store Manager Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP sales cube

  - CUSTINVOICETRANSEXPANDED table

  - RETAILHOUR table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


