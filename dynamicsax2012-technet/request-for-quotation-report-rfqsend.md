---
title: Request for quotation report (RFQSend)
TOCTitle: Request for quotation report (RFQSend)
ms:assetid: 2a7c5d99-d360-414c-9c44-457f819d96c1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242458(v=AX.60)
ms:contentKeyID: 36057757
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- request for quote
- RFQ
- SSRS_Reports.Reports.RFQSend
- request for quotation
- send RFQ
---

# Request for quotation report (RFQSend) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays the details about a request for quotation (RFQ) for a specific vendor. You can send the report to the selected vendor.

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
<td><p>RFQSend</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RFQSend</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RFQSend</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Common</strong> &gt; <strong>Requests for quotations</strong> &gt; <strong>All requests for quotations</strong>. On the <strong>All requests for quotations</strong> list page, select an RFQ that has a lowest status of <strong>Created</strong>. On the <strong>Action Pane</strong>, on the <strong>Quotation</strong> tab, in the <strong>Process</strong> group, click <strong>Send</strong>. In the <strong>Sending request for quotation</strong> form, on the top menu, click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PurchRFQSendTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the RFQSendDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

