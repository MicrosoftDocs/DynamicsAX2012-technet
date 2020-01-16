---
title: Return order registered and received report (ReturnAcknowledgmentAndDocument)
TOCTitle: Return order registered and received report (ReturnAcknowledgmentAndDocument)
ms:assetid: 8e6c158b-d88a-46b2-89ee-78dea7c5b0e3
ms:mtpsurl: https://technet.microsoft.com/library/Hh227436(v=AX.60)
ms:contentKeyID: 36059739
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ReturnAcknowledgmentAndDocument
---

# Return order registered and received report (ReturnAcknowledgmentAndDocument) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Return order registered and received** report as a return order that documents that the customer is authorized to return a specified quantity of purchased goods. When you generate and print the report, no changes in the status of the return order occur and the event is not journalized. The report can also be used as a return acknowledgement to document receipt of the returned items.

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
<td><p>Print notes</p></td>
<td><p>Select this check box to print notes marked as external on the return order header.</p></td>
</tr>
<tr class="even">
<td><p>Send electronically</p></td>
<td><p>Select this check box to send the return order document electronically.</p></td>
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
<td><p>ReturnAcknowledgmentAndDocument</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ReturnAcknowledgmentAndDocument</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ReturnAcknowledgment</p>
<p>ReturnAcknowledgment_Action</p>
<p>ReturnDocument</p>
<p>ReturnDocument_Action</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Common</strong> &gt; <strong>Return orders</strong> &gt; <strong>All return orders</strong>. Click <strong>Return order</strong> or <strong>Acknowledgement</strong> under <strong>Send</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ReturnAcknowledgmentAndDocumentTmp table


> [!NOTE]
> <P>To learn where the data in the temp table comes from, view the cross-references for the ReturnAcknowledgmentAndDocumentDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Return orders (form)](https://technet.microsoft.com/library/hh803010\(v=ax.60\))

  


