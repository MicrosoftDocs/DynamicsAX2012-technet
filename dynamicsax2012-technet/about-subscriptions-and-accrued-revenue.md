---
title: About subscriptions and accrued revenue
TOCTitle: About subscriptions and accrued revenue
ms:assetid: b2afed31-0cbc-4d6d-8ac3-e31030ee95a7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571880(v=AX.60)
ms:contentKeyID: 42117771
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accrue revenue
- accrued revenue
- subscription revenue
---

# About subscriptions and accrued revenue [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A subscription is an agreement between your organization and a customer. This agreement requires the customer to prepay for periodic or regular services. A subscription can be used for **Fee - subscription** transactions that are created for a Time and material project. These transactions are then applied to the **Accrued revenue - subscription** account. The transactions can also be viewed in a profit and loss statement.

To post the accrued revenue on a subscription, the **Accrue revenue** check box in the **Subscription groups** form must be selected for the subscription group that the subscription is assigned to.

When you invoice transactions for which revenue has been accrued, the **Accrued revenue - subscription** account is debited by the same amount that the **Invoiced revenue** account is credited. As a result, revenue in the profit and loss account becomes 0 (zero).

When accrued revenue is posted, the **WIP - subscription** account is debited by the accrual amount, and the **Accrued revenue - subscription** account is credited by the accrual amount.

If you reverse an accrued transaction, the **Accrued revenue - subscription** account is debited by the same amount that the **WIP - subscription** account is credited.


> [!NOTE]
> <P>You cannot post accrued revenue until the invoice for the subscription is posted.</P>



## See also

[Accrue subscription revenue](accrue-subscription-revenue.md)

[Configuring accrued revenue and matching principles](configuring-accrued-revenue-and-matching-principles.md)

[About accrued revenue](about-accrued-revenue.md)

[Subscription groups (form)](https://technet.microsoft.com/en-us/library/aa553150\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

