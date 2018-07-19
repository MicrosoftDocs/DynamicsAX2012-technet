---
title: About sealed bids
TOCTitle: About sealed bids
ms:assetid: 79ecccb3-846b-4c45-87db-e884649f916d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn621057(v=AX.60)
ms:contentKeyID: 62200101
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- procurement
- PurchRFQCaseTable
- PurchRFQReplyTable
- sealed bid
- sealed bids
- sealed RFQ
- sealed replies
- sealed reply
- sealed request for quotation
- sealed RFQs
audience: Application User
ms.search.region: Global
---

# About sealed bids 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This feature is available only if **eProcurement** in Microsoft Dynamics AX 2012 R3 is installed.

Sealed requests for quotation (RFQs) and sealed bids promote fair procurement practices. By using sealed bids on an RFQ, the details, such as costs and quantities, are masked or hidden for confidentiality until the purchasing agent unseals the RFQ after it expires. Vendors can see their own bid details at any time. If the purchasing agent receives any bids on the RFQ through other methods, such as mail, email, or fax, they can be entered in Microsoft Dynamics AX 2012 R3 only after the electronic bids are unsealed in AX 2012 R3.


> [!NOTE]
> <P>Vendors can use sealed bid functionality with the Vendor portal on Enterprise Portal for Microsoft Dynamics AX only, this functionality is not available in Sites Services for Microsoft Dynamics ERP.</P>



## Sealing an RFQ

You can enable vendors to submit sealed bids, by selecting **Sealed** in the **Request for quotation details** form, in the **Bid type** field.

RFQ replies that you receive will be hidden until the RFQ’s expiration date, when you open the RFQ and start bid tabulation.


> [!WARNING]
> <P>After an RFQ is sealed, it cannot be unsealed before the expiration date and time, and the bid type cannot be changed.</P>



For more information, see [Create a request for quotation](create-a-request-for-quotation.md).

## Opening a sealed bid

When the expiration date and time for a sealed RFQ passes, the purchasing agent can unseal the bids that have come in reply to it, by clicking **Unseal bids**, on the **Action Pane**, in the **Request for quotation reply** form.


> [!WARNING]
> <P>When one bid on a sealed RFQ is unsealed, all bids for the RFQ are unsealed; lines and quantities in the bids then become visible, and can no longer be resealed or hidden.</P>



For more information, see [Compare bids and award a contract](compare-bids-and-award-a-contract.md).

  


