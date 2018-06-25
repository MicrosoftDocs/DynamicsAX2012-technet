---
title: About derived value models
TOCTitle: About derived value models
ms:assetid: a4649e74-1689-4036-bac3-887b1b839dd0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550176(v=AX.60)
ms:contentKeyID: 36058818
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- derived value models
- fixed asset value models
- value models
---

# About derived value models [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The purpose of derived value models is to simplify the posting of fixed asset value model transactions that are planned for regular intervals.

You choose one value model as the primary value model. This usually is the value model that is used for accounting depreciation. You then attach to it other value models that are set up to post transactions in the same intervals as the primary value model. Tax depreciation value models are often set up as derived value models.

The most common transactions to set up to post to derived value models are acquisitions, acquisition adjustments, and disposals.

**Example**

Value model B and value model C are set up as derived value models for value model A for the **Acquisition** transaction type. In value model A, you enter an acquisition transaction for asset 123 for 1,500.00. When the transaction is posted, an acquisition transaction is generated and posted in asset 123 for value model B and in asset 123 for value model C for 1,500.00.

When you prepare the transactions of the primary value model for posting in the fixed asset journal, you can also view and modify the transactions of the derived value models. If you prepare the primary value model transactions in another journal, the transactions of the derived value are not displayed. However, they are posted to the appropriate accounts and posting layers when you post the primary value model transactions.


> [!NOTE]
> <P>Value models that are set up to post transactions at intervals other than the primary value model intervals must be attached to the fixed asset as separate value models and not as derived value models.</P>



## See also

[Set up value models](set-up-value-models.md)

[About posting with derived value models](about-posting-with-derived-value-models.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

