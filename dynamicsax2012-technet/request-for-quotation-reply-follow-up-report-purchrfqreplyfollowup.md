---
title: Request for quotation reply follow-up report (PurchRFQReplyFollowUp)
TOCTitle: Request for quotation reply follow-up report (PurchRFQReplyFollowUp)
ms:assetid: 64bfa479-c6f9-48bd-96d2-658af2138070
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433499(v=AX.60)
ms:contentKeyID: 36941266
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.PurchRFQReplyFollowUp
---

# Request for quotation reply follow-up report (PurchRFQReplyFollowUp) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays the details about vendor replies to a request for quotation (RFQ) that you might want to follow up on.

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
<td><p><strong>Item number</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Requests for quotations follow-up</strong> form, select an item. To add more than one item, click <strong>Add</strong>. Only the RFQ replies that contain the selected line item are displayed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Expiration date</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Requests for quotations follow-up</strong> form, select a date that the RFQ replies are valid to.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Request for quotation</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Requests for quotations follow-up</strong> form, select a specific RFQ. Only the replies to the selected RFQ are displayed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Status</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Requests for quotations follow-up</strong> form, select an RFQ reply status to include on the report. To add more than one status, click <strong>Add</strong>. Only the RFQs that have the selected status are displayed on the report.</p></td>
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
<td><p>PurchRFQReplyFollowUp</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PurchRFQReplyFollowUp</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PurchRFQReplyFollowUp</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Periodic</strong> &gt; <strong>Requests for quotations</strong> &gt; <strong>Request for quotation follow-up</strong>. In the <strong>Request for quotation follow-up</strong> form, use the filters to select the RFQ or group of RFQs that you want to follow up on. On the top menu, click <strong>Follow-up report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - EcoResCategory table

  - PurchRFQLine table

  - PurchRFQTable

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Request for quotation follow-up (form)](https://technet.microsoft.com/en-us/library/hh227392\(v=ax.60\))

[Follow up on requests for quotation and replies](follow-up-on-requests-for-quotation-and-replies.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

