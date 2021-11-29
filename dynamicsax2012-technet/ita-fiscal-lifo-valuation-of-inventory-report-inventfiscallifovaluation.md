---
title: (ITA) Fiscal LIFO valuation of Inventory report (InventFiscalLIFOValuation)
TOCTitle: (ITA) Fiscal LIFO valuation of Inventory report (InventFiscalLIFOValuation)
ms:assetid: d0691437-6a16-4dcd-be95-b3a01ede6956
ms:mtpsurl: https://technet.microsoft.com/library/Hh456300(v=AX.60)
ms:contentKeyID: 36997726
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Print
- report
- SSRS_Reports.Reports.InventFiscalLIFOValuation
- (ITA)
---

# (ITA) Fiscal LIFO valuation of Inventory report (InventFiscalLIFOValuation) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Fiscal LIFO valuation of Inventory** report displays and prints the details of inventory item values by using the Last in, first out (LIFO) valuation method. This report is typically used by chief executive officers, chief financial officers, accountants, accounting managers, finance controllers, and clerks to maintain the invoice process and cash process.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p>InventFiscalLIFOValuation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventFiscalLIFOValuation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventFiscalLIFOValuation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Journals</strong> &gt; <strong>Fiscal LIFO</strong> &gt; <strong>Fiscal lifo internal</strong>. Click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InventFiscalLIFOValuationTmp table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the InventFiscalLIFOValuationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About LIFO with physical value and marking](about-lifo-with-physical-value-and-marking.md)

  


