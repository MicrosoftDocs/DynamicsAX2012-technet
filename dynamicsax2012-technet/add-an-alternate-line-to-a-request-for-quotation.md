---
title: Add an alternate line to a request for quotation
TOCTitle: Add an alternate line to a request for quotation
ms:assetid: bc0544da-4729-44d1-821b-99a5ec07d1f1
ms:mtpsurl: https://technet.microsoft.com/library/Dn621061(v=AX.60)
ms:contentKeyID: 62200148
author: tfehr
ms.author: daxcpft
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- line
- RFQ
- request for quotation
- requests for quotations
- lines
- alternate
- request for quotations
- requests for quotation
- RFQs
- PurchRFQCaseTableListPage
- PurchRFQReplyTableListPage
- alternate line
- alternates
- substitute
- quote, procurement
- substitutes
audience: Application User
ms.search.region: Global
---

# Add an alternate line to a request for quotation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This feature is available only if **eProcurement** in Microsoft Dynamics AX 2012 R3 is installed.

 Microsoft Dynamics AX 2012 R3 enables vendors to add alternates to their bids. As a purchasing agent, you might want to know about alternate items or services, in case there are better alternatives to your original request, or if the item or service has changed. A vendor might want to offer additional variety or new models. You must enable this functionality in the settings for the request for quotation (RFQ).


> [!NOTE]
> <P>If the purchase type is <STRONG>Purchase requisition</STRONG> and alternate lines are present, you can accept either the original bid line or its alternate, but not both. Alternates that are approved are reflected in the purchase requisition.</P>
> <P>Additionally, when you review total costs in the bid, be aware that the alternate lines are not included in the total.</P>



## Allow alternate lines in an RFQ

Use this procedure if you want vendors to be able to include substitutes or alternates in their bids.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Open the RFQ that you want to work with.

3.  In the **Request for quotation header**, under **Request for quotation information**, select the **Allow alternates on response lines** check box.

## Create alternate lines in an RFQ reply

If the functionality for adding alternates has been enabled, use this procedure if you are a purchasing agent and want to add alternate lines when you define an RFQ reply form in advance. The status of the RFQ must be **Sent**. Only non-catalog items (category items) can have alternates. For more information, see [Create a reply to a request for quotation](create-a-reply-to-a-request-for-quotation.md).


> [!NOTE]
> <P>If you are a vendor and want to add alternate lines when you reply to an RFQ in the Vendor portal on Enterprise Portal for Microsoft Dynamics AX, see <A href="view-and-reply-to-a-request-for-quotation.md">View and reply to a request for quotation</A>. If you are a Public sector vendor, see <A href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</A>.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  On the **Request for quotation replies** list page, open the RFQ reply that you want to work with. On the **Action Pane**, on the **Reply** tab, click **Edit**.

3.  On the **Purchase quotation lines** FastTab, select the category line under which the alternate should appear.

4.  Click **Add alternate**.

5.  Enter information about the product, such as the item number or procurement category, quantity, price, and discount.

## See also

[Create a request for quotation](create-a-request-for-quotation.md)

[Modify a request for quotation](modify-a-request-for-quotation.md)

[Compare bids and award a contract](compare-bids-and-award-a-contract.md)

  


