---
title: Purchase requisition report (PurchReq)
TOCTitle: Purchase requisition report (PurchReq)
ms:assetid: a4149227-e3dd-4ce1-8da8-8a0e8cda44df
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335163(v=AX.60)
ms:contentKeyID: 36687376
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.PurchReq
---

# Purchase requisition report (PurchReq) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Purchase requisition** report displays the header and line details for a selected purchase requisition. You can also view the itemized total amounts for the purchase requisition lines, including any discounts and taxes that were applied. You can generate a purchase requisition report only if the purchase requisition has been submitted for review.

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
<td><p>PurchReq</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PurchReq</p></td>
</tr>
<tr class="odd">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Common</strong> &gt; <strong>Purchase requisitions</strong> &gt; <strong>Purchase requisitions prepared by me</strong>. On the <strong>Purchase requisitions prepared by me</strong> list page, select the purchase requisition that you want to view versions for. On the <strong>Action Pane</strong>, on the <strong>Review</strong> tab, click <strong>Purchase requisition versions</strong>. In the <strong>Purchase requisition versions</strong> form, click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PurchReqTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the PurchReqDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[View the history for a purchase requisition](view-the-history-for-a-purchase-requisition.md)

[Purchase requisition versions (form)](https://technet.microsoft.com/en-us/library/hh242467\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

