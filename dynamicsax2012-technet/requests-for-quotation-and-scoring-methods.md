---
title: Requests for quotation and scoring methods
TOCTitle: Requests for quotation and scoring methods
ms:assetid: 55a51918-d1dc-4527-9b43-cd20214dcab7
ms:mtpsurl: https://technet.microsoft.com/library/Dn621054(v=AX.60)
ms:contentKeyID: 62200071
author: tonyafehr
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- quotes
- RFQ
- procurement
- request for quotation
- requests for quotations
- score
- PurchRFQCaseTable
- quote
- request for quotations
- requests for quotation
- RFQs
- scores
- scoring method
- scoring methods
audience: Application User
ms.search.region: Global
---

# Requests for quotation and scoring methods 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This feature is available only if **eProcurement** in Microsoft Dynamics AX 2012 R3 is installed.

Assigning a score to a bid is useful when you compare replies to requests for quotation (bids). This topic contains frequently asked questions that you might have about scoring methods and criteria.

A scoring method consists of a set of scoring criteria that apply to the RFQ case. For example, you might want to rate a vendor on past performance, or rate whether the company is environmentally friendly or a good collaborator, or give a score based on price. Typically, a purchasing manager creates scoring methods and criteria for purchasing agents to use. One or more methods and criteria can then be assigned as a default for a solicitation type, so that when you create a new RFQ of that type, the set of criteria defined by the method is automatically applied to the case that you create. For more information, see [Create and use a solicitation type](create-and-use-a-solicitation-type.md).

## How do I create scoring methods and criteria?

Typically, you first create the method, and give it a name and description that indicate the type of criteria you’ll be rating, such as price. Then you create the criteria, which could be unit price or discount, for example, and you create a range for scoring, such as currency or points.

You perform these tasks on the **Scoring method** form. (Click **Procurement and sourcing** \> **Setup** \> **Request for quotation** \> **Scoring method**.) For more information, see [Create and use scoring criteria and methods](create-and-use-scoring-criteria-and-methods.md).

## How do I apply a scoring method to my RFQ?

You apply the scoring method to the RFQ on the **Request for quotation details** page, by clicking **Scoring criteria** on the **Action pane**. You can also change an existing method, and you can add or delete criteria, if no scoring has been done for any of the RFQ replies. For more information, see [Create and use scoring criteria and methods](create-and-use-scoring-criteria-and-methods.md).

## Where do I assign scores to received bids?

When you receive a reply to your RFQ (a bid), open it, and fill in the scores for your criteria on the **Requests for quotations reply details** form, on the **Bid scoring** FastTab. When all the bids are scored, you can compare the scores and rank them. For more information, see [Compare bids and award a contract](compare-bids-and-award-a-contract.md).

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Create and use a solicitation type](create-and-use-a-solicitation-type.md)

  


