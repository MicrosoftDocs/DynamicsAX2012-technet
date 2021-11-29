---
title: Posting fixed asset transactions to posting layers
TOCTitle: Posting fixed asset transactions to posting layers
ms:assetid: 18613bf1-5002-4ae3-8017-1a6d420b5504
ms:mtpsurl: https://technet.microsoft.com/library/Aa569909(v=AX.60)
ms:contentKeyID: 36056098
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Posting fixed asset transactions to posting layers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A fixed asset is often depreciated in different ways for different purposes. Depreciation for tax purposes is calculated by current tax rules to achieve the highest possible depreciation before taxes, but depreciation for reporting purposes is calculated according to accounting laws and standards. The various kinds of depreciation are calculated and recorded separately in the posting layers.

Each value model that is attached to a fixed asset is set up for a particular posting layer that has an overall depreciation objective. There are three types of posting layers. **Current** and **Operations** are used for accounting purposes, and **Tax** is used for tax depreciation. You can use depreciation books instead of the tax layer, if you prefer.

Each journal that you can post depreciations in is defined by its journal name for only one posting layer. The posting layer in the journal cannot be changed, which helps make sure that transactions for each posting layer are kept separate. At least one journal name must be created for each posting layer.

You can designate ledger accounts for fixed asset transactions in the **Fixed asset posting profiles** form. For each posting profile, you must select the relevant transaction type and value model, with the relevant posting layer, and then designate the ledger accounts. If special accounts for tax depreciation are created, they are often put at the end of the chart of accounts and have account numbers that differ from the account numbers for usual business.


> [!NOTE]
> <P>Using derived value models lets you post transactions to different posting layers at the same time. You create the transactions of the primary value model in a journal with the posting layer that corresponds to the value model posting layer. During posting, the derived value model transactions are posted to their respective posting layers.</P>



## See also

[Set up value models](set-up-value-models.md)

[Set up journal names](set-up-journal-names.md)

[About derived value models](about-derived-value-models.md)

[About posting with derived value models](about-posting-with-derived-value-models.md)

  


