---
title: Define request for quotation replies
TOCTitle: Define request for quotation replies
ms:assetid: 356ed9ce-83c0-4a51-831e-ba9008bf0b91
ms:mtpsurl: https://technet.microsoft.com/library/Gg231091(v=AX.60)
ms:contentKeyID: 36056558
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- replies
- request for quote
- RFQ
- RFQ reply
- procurement
- request for quotation
- requests for quotations
- Forms.PurchRFQReplyFields
- reply
- quote
- request for quotations
- requests for quotation
- RFQs
- bid
- bids
- MsDynAx060.Forms.PurchRFQReplyFields
audience: Application User
ms.search.region: Global
---

# Define request for quotation replies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to specify the information that you want to receive from vendors when they reply to (bid on) a request for quotation (RFQ). The fields that you select in the **Default request for quotation reply fields** form are printed on the RFQ reply sheet that you send to vendors. These fields are also included on the RFQ return document that you can send to vendors if, for example, you want to negotiate prices or delivery times.

You can either define default reply fields that apply to all RFQs, or you can define fields that apply to a specific RFQ.

## Define default reply fields

Use this procedure to specify RFQ reply fields that will apply to all RFQs.

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  Click **Request for quotation**, and then click **Default request for quotation reply fields**.

3.  Select or clear the check boxes that correspond to the information that you want to receive from vendors in their bids.

## Define reply fields for a specific RFQ

Use this procedure to change a specific RFQ’s reply fields from the default settings.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select the RFQ for which you want to change the configuration of the RFQ reply.

3.  On the **Action Pane**, on the **Quotation** tab, click **Set RFQ reply defaults**.

4.  In the **Default request for quotation reply fields** form, select or clear the check boxes that correspond to the information that you want to receive. These changes only apply to the selected RFQ.

## See also

[Create a reply to a request for quotation](create-a-reply-to-a-request-for-quotation.md)

[Default request for quotation reply fields (form)](https://technet.microsoft.com/library/hh227599\(v=ax.60\))

  


