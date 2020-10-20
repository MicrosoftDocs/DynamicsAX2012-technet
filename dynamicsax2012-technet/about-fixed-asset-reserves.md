---
title: About fixed asset reserves
TOCTitle: About fixed asset reserves
ms:assetid: f7e28b14-0617-4650-acf3-9b1037f59f5e
ms:mtpsurl: https://technet.microsoft.com/library/Aa499813(v=AX.60)
ms:contentKeyID: 36060043
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- asset reverse
- asset reverses
- fixed assets reverse
- fixed assets reverses
- fixed asset reverses
- fixed asset reverse
audience: Application User
ms.search.region: Global
---

# About fixed asset reserves 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

On the **Ledger accounts** tab in the **Fixed asset posting profiles** form, select **Provision for reserve** or **Transfer from reserve** to set up accounts to post provisions for reserve or transfers from reserve amounts to the general ledger.

**Provision for reserve** and **Transfer from reserve** are transaction types that are used only for the reserves of sales of fixed assets with profit.

Usually, when a fixed asset is sold with profit, the profit has to be recognized in the year of sale and then posted to the profit and loss part of the chart of accounts.

However, in some countries/regions, legislation lets you postpone profit recognition (and taxation) to later years. **Provision for reserve** and **Transfer from reserve** meet these requirements.

## Provision for reserve

When a fixed asset is sold with a profit, the profit can be credited to a **Provision for reserve** account, which should be set up as a balance sheet account. Later, this reserve is dissolved when a replacement fixed asset is acquired or when the legal deadline for dissolution of the reserve expires.

The **Provision for reserve** account is used for posting the profit to a balance sheet account. Therefore, the ledger account is in the liability part of the balance sheet. The offset account removes the provision amount, which is the difference between the sales price and the net book value, from the fixed asset value, and then sets the value of the fixed asset to zero.

## Transfer from reserve

The **Transfer from reserve** accounts are for dissolution of the reserves. The ledger account is used for revenue recognition of the deferred profit and the offset account offsets the ledger account for **Provision for reserve**.

## See also

[Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md)

  


