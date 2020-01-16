---
title: About requests for quotation
TOCTitle: About requests for quotation
ms:assetid: 773eee02-844c-4421-b265-b3b91a8ff33e
ms:mtpsurl: https://technet.microsoft.com/library/Gg212988(v=AX.60)
ms:contentKeyID: 36058207
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- IFB
- quotes
- request for quote
- RFQ
- procurement
- request for quotation
- requests for quotations
- Forms.VendRFQJournal
- ITB
- quote
- request for quotations
- requests for quotation
- RFQs
- MsDynAx060.Forms.VendRFQJournal
- IFBs
- invitation for bid
- invitation to bid
- invitation for bids
- ITBs
audience: Application User
ms.search.region: Global
---

# About requests for quotation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Organizations issue a request for quotation (RFQ) when they want to purchase items or services, and want to receive competitive offers from several vendors. In an RFQ, you ask vendors to provide the prices and delivery times for the quantities of items that you specify. You can also ask vendors to specify whether there are any incidental charges, such as shipping costs, or whether the vendor offers discounts for large orders or early payment of the vendor invoice.

The RFQ process covers:

  - Creating and sending an RFQ to one or more vendors.

  - Receiving and registering RFQ replies (bids).

  - Transferring accepted bids to a purchase order.

The following illustration provides an overview of the RFQ process.

![Request for quote process](images/Gg212988.RFQProcess(AX.60).gif "Request for quote process")

## Set up RFQ functionality

Before you can create an RFQ, you must set up RFQ information in Microsoft Dynamics AX 2012 R3.

For more information, see [Set up requests for quotation](set-up-requests-for-quotation.md).

## Create and send an RFQ

You create the RFQ, select the vendors that you want to bid on the RFQ, and then send the RFQ to the vendors. You can publish it to a website by using online services for Microsoft Dynamics ERP or publish it on Enterprise Portal for Microsoft Dynamics AX.

You can create an RFQ only for the **Purchase order** purchase type. If the RFQ is created from a purchase requisition, the **Purchase requisition** type is automatically assigned to the RFQ.

For RFQs that have the **Purchase order** type, inventory transactions that have the receipt status of **Quotation receipt** are created when RFQ lines are created.

For more information, see the following topics:

[Create a request for quotation](create-a-request-for-quotation.md)

[Create a request for quotation from a purchase requisition](create-a-request-for-quotation-from-a-purchase-requisition.md)

[(USA) Request quotations online with Sites Services](usa-request-quotations-online-with-sites-services.md)

## Receive and register RFQ replies (bids)

As you receive replies to an RFQ, enter the information from each vendor on a vendor-specific RFQ reply sheet. This enables you to compare what you requested to the bids from each vendor. If you are using AX 2012 R3, this can include scoring and ranking the bids.

With RFQs that appear on Enterprise Portal or online services, you can download replies directly into an RFQ reply form in the Microsoft Dynamics AX client.

You can set up the system to receive alerts when the RFQ expiration date is reached. By using the notifications, you can follow up on the RFQ to see whether you have received bids from all vendors. You can also compare the vendor bids by ranking them according to your scoring criteria, such as best total price or best total delivery time.

For more information, see the following topics:

[Create a reply to a request for quotation](create-a-reply-to-a-request-for-quotation.md)

[Follow up on requests for quotation and replies](follow-up-on-requests-for-quotation-and-replies.md)

[Create and use scoring criteria and methods](create-and-use-scoring-criteria-and-methods.md)

[About alerts](about-alerts.md)

## Transfer accepted bids to a purchase order

After you have identified the best bid, such as the bid that offers the best total price, you accept the bid. The status of the vendor-specific RFQ reply is updated to **Accepted**. When you accept the bid, a purchase order is created automatically, and you can reject bids from the other vendors.

For more information, see the following topics:

[Compare bids and award a contract](compare-bids-and-award-a-contract.md)

[About request for quotation statuses](about-request-for-quotation-statuses.md)

## RFQs and master planning

When supplies are calculated in a master plan, the calculations can include RFQ lines that have inventory transactions with a status of **Quotation receipt**. If no inventory transactions exist for an RFQ line, the RFQ line is not considered a supply.

  


