---
title: About derived depreciation books
TOCTitle: About derived depreciation books
ms:assetid: 28f9a89b-f928-4ae2-9452-d390bea9eb10
ms:mtpsurl: https://technet.microsoft.com/library/Aa496845(v=AX.60)
ms:contentKeyID: 36056218
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation
- derived depreciation
- fixed asset depreciation
- fixed asset derived depreciation
audience: Application User
ms.search.region: Global
---

# About derived depreciation books 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Setting up derived depreciation books lets you enter a transaction once and update multiple fixed assets and books. You select a value model, which usually is the value model that is used for accounting depreciation. You then attach the value model to other depreciation books that are set up to post transactions in the same intervals as the value model.

The most common transactions to set up to post to derived depreciation books are acquisitions, acquisition adjustments, and disposals.

For example, assume that depreciation book B and depreciation book C are set up as derived depreciation books for value model A for the **Acquisition** transaction type. For value model A, enter an acquisition transaction for asset 123 for 1,500.00. When it is posted, an acquisition transaction for asset 123 in depreciation book B and asset 123 for depreciation book C for 1,500.00 will be generated and posted.

When you prepare the transactions of the value model for posting in the fixed asset journal, you can also view and modify the transactions of the derived depreciation books. If you prepare the value model transactions in another journal, you cannot view the transactions of the derived depreciation books. However, they are posted to the appropriate accounts and posting layers when you post the value model transactions.


> [!NOTE]
> <P>If depreciation books are set up to depreciate at different intervals or methods, the <STRONG>Depreciation</STRONG> transaction type should not be set up as derived.</P>



## See also

[Set up asset depreciation books](set-up-asset-depreciation-books.md)

  


