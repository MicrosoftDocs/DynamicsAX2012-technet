---
title: About travel and expense policies
TOCTitle: About travel and expense policies
ms:assetid: 7112699b-aacf-41c0-9d17-8b8c61c95a86
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231832(v=AX.60)
ms:contentKeyID: 36058064
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About travel and expense policies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can define policies that your workers must follow when entering and submitting expense reports and travel requisitions. Implementing travel and expense policies can help you manage expenses effectively.

For example, you can set a policy that for New York City the hotel expense per night cannot exceed USD 250. If a worker submits an expense report or a travel requisition in which the room rate exceeds this amount, the system will notify the worker that the policy amount for the expense has been exceeded. You can configure the message that the worker will receive when you define the policy.

You can define three types of policies:

  - Warning – Allows the worker to submit an expense report or travel requisition but the expense will be marked for all approvers and for later reporting.

  - Error – Requires the worker to revise the expense to comply with the policy before submitting the expense report or travel requisition.

  - Justification – Requires the worker or a manager to enter a justification for exceeding the policy amount before submitting the expense report or travel requisition.

You can also set up a date range for which expense policies are in effect. For example, airline fares for flights between Denmark and New York City can be expensive during the peak holiday travel season. You can define a flight expense rule that restricts the cost of flights to New York City to a limit of DKK 5000 and you can specify that this rule be in effect between March 15 and September 15.

## See also

[Create policies](create-policies.md)

  


