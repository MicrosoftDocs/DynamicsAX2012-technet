---
title: Retail sales by store report (RetailSalesByStore)
TOCTitle: Retail sales by store report (RetailSalesByStore)
ms:assetid: 56320442-923b-480c-94fa-85336578b584
ms:mtpsurl: https://technet.microsoft.com/library/Hh697612(v=AX.60)
ms:contentKeyID: 42518421
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Retail sales by store report (RetailSalesByStore) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the sales performance for stores within a given date range. The report displays the sales performance of all stores that the user is assigned to, and also includes the store name, amount, cost of goods sold, quantity, profit margin, and profit margin percentage.


> [!NOTE]
> <P>This report is designed to use in Enterprise Portal for Microsoft Dynamics AX.</P>



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
<td><p>RetailSalesByStore</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailSalesByStore</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailSalesByStore</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is not available in the Microsoft Dynamics AX client. However, this report is available in Enterprise Portal.</p>
Click the <strong>Retail</strong> tab, and select the <strong>Sales by store</strong> report. Specify a date range by using the <strong>From date</strong> and <strong>To date</strong> fields, and then click <strong>View report</strong>.</td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - CUSTINVOICETRANSEXPANDED table

  - RETAILCHANNELVIEW table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


