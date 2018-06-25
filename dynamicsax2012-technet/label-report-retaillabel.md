---
title: Label report (RetailLabel)
TOCTitle: Label report (RetailLabel)
ms:assetid: c94af841-cc97-434e-af83-60e485f11c87
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh697695(v=AX.60)
ms:contentKeyID: 42518523
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Label report (RetailLabel) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print or reprint shelf labels or product labels. A standard report format for printing shelf and product labels is provided, but you can add additional label formats.

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
<td><p>RetailLabel</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailLabel</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailLabelA4Landscape3X5_Item</p>
<p>RetailLabelA4Portrait3X5_Shelf</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Periodic</strong> &gt; <strong>Bar codes and labels</strong> &gt; <strong>Print shelf labels</strong>. In the <strong>Shelf label printing</strong> form, click <strong>Print</strong>. Then click <strong>Print labels</strong> or <strong>Reprint labels</strong>.</p>
<p>–or–</p>
<p>Click <strong>Retail</strong> &gt; <strong>Periodic</strong> &gt; <strong>Bar codes and labels</strong> &gt; <strong>Print product labels</strong>. In the <strong>Product label printing</strong> form, click <strong>Print</strong>. Then click <strong>Print labels</strong> or <strong>Reprint labels</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - RetailLabelTmp table

  - RetailLabelDP.processReport


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the RetailLabelDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

