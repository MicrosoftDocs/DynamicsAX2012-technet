---
title: About request for quotation statuses
TOCTitle: About request for quotation statuses
ms:assetid: 3b97a16c-e29e-48c0-a54b-2cf14dbf2885
ms:mtpsurl: https://technet.microsoft.com/library/Gg231148(v=AX.60)
ms:contentKeyID: 36056650
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- status
- RFQ
- procurement
- request for quotation
- requests for quotations
- Forms.VendRFQJournal
- quote
- request for quotations
- requests for quotation
- RFQs
- PurchRFQCaseTableListPage
- MsDynAx060.Forms.VendRFQJournal
- statuses
audience: Application User
ms.search.region: Global
---

# About request for quotation statuses 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The status of a request for quotation (RFQ) is shown in the RFQ header and depends on the statuses of the RFQ lines. The status indicates the extent to which you have processed the RFQ. Each RFQ has two values for the status: lowest and highest. The lowest status is the least advanced stage of any line in the RFQ, and the highest status is the most advanced stage of any line in the RFQ. For example, if the least advanced stage in an RFQ is for a line that has been created, the lowest status for the RFQ is **Created**. If the most advanced stage in the RFQ is for a line that has been sent to vendors, the highest status for the RFQ is **Sent**. The statuses are automatically updated as you process an RFQ.

You can view the lowest and highest statuses for an RFQ header on the **All requests for quotations** list page. You can view the lowest and highest statuses for an RFQ line on the **Lines** tab in the RFQ form.

The sequence of statuses for processing an RFQ is as follows:

  - **Created**

  - **Sent**

  - **Received**

  - **Accepted**/**Canceled**/**Rejected**

The lowest and highest statuses of an RFQ can change throughout the RFQ process.

## Creating and sending an RFQ

The following table shows RFQ status changes when you create an RFQ and send it to vendors.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Action</p></th>
<th><p>Lowest RFQ header status</p></th>
<th><p>Highest RFQ header status</p></th>
<th><p>Lowest RFQ line status</p></th>
<th><p>Highest RFQ line status</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create the RFQ header and line.</p></td>
<td><p>Created</p></td>
<td><p>Created</p></td>
<td><p>Created</p></td>
<td><p>Created</p></td>
</tr>
<tr class="even">
<td><p>Send the RFQ to a specific vendor.</p></td>
<td><p>Sent</p></td>
<td><p>Sent</p></td>
<td><p>Sent</p></td>
<td><p>Sent</p></td>
</tr>
<tr class="odd">
<td><p>Add another vendor.</p></td>
<td><p>Created</p></td>
<td><p>Sent<br />
(The RFQ has been sent to only one vendor.)</p></td>
<td><p>Created</p></td>
<td><p>Sent</p></td>
</tr>
<tr class="even">
<td><p>Send the RFQ to the second vendor.</p></td>
<td><p>Sent</p></td>
<td><p>Sent</p></td>
<td><p>Sent</p></td>
<td><p>Sent</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>You can add more vendors to an RFQ at any time, and the lowest and highest statuses change to reflect the vendors that were added. For example, if you received bids from all vendors and accepted at least one line on a bid, the lowest status in the RFQ header is <STRONG>Rejected</STRONG>, and the highest status is <STRONG>Accepted</STRONG>. If you add a new vendor, the lowest status on any line is now <STRONG>Created</STRONG>. Therefore, the lowest status in the RFQ header changes to <STRONG>Created</STRONG>, and the highest status remains <STRONG>Accepted</STRONG>.</P>



For more information about how to create an RFQ, see [Create a request for quotation](create-a-request-for-quotation.md).

## Receiving and registering bids

The following table shows RFQ status changes as you receive bids and register the information in the RFQ reply sheet.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Action</p></th>
<th><p>Lowest bid status</p></th>
<th><p>Highest bid status</p></th>
<th><p>Lowest RFQ header status</p></th>
<th><p>Highest RFQ header status</p></th>
<th><p>Lowest RFQ line status</p></th>
<th><p>Highest RFQ line status</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Register one vendor’s bid, and save it.</p></td>
<td><p>Sent</p></td>
<td><p>Received</p></td>
<td><p>Sent</p></td>
<td><p>Received</p></td>
<td><p>Sent</p></td>
<td><p>Received</p></td>
</tr>
<tr class="even">
<td><p>Register the second vendor’s bid, and save it.</p></td>
<td><p>Received</p></td>
<td><p>Received</p></td>
<td><p>Received</p></td>
<td><p>Received</p></td>
<td><p>Received</p></td>
<td><p>Received</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If you return a bid to a vendor for additional negotiation, the lowest and highest statuses both remain <STRONG>Received</STRONG>.</P>



For more information about how to register a bid, see [Create a reply to a request for quotation](create-a-reply-to-a-request-for-quotation.md).

## Accepting a bid

The following table shows RFQ status changes as you accept and reject vendors’ bids.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Action</p></th>
<th><p>Lowest bid status</p></th>
<th><p>Highest bid status</p></th>
<th><p>Lowest RFQ header status</p></th>
<th><p>Highest RFQ header status</p></th>
<th><p>Lowest RFQ line status</p></th>
<th><p>Highest RFQ line status</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accept one of the bids.</p></td>
<td><p>Received</p></td>
<td><p>Accepted</p></td>
<td><p>Received</p></td>
<td><p>Accepted</p></td>
<td><p>Received</p></td>
<td><p>Accepted</p></td>
</tr>
<tr class="even">
<td><p>Reject the other bid.</p></td>
<td><p>Rejected</p></td>
<td><p>Accepted</p></td>
<td><p>Rejected</p></td>
<td><p>Accepted</p></td>
<td><p>Rejected</p></td>
<td><p>Accepted</p></td>
</tr>
</tbody>
</table>


For more information about how to accept and reject bids, see [Compare bids and award a contract](compare-bids-and-award-a-contract.md).

  


