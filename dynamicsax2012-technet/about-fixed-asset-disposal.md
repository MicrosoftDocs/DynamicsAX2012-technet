---
title: About fixed asset disposal
TOCTitle: About fixed asset disposal
ms:assetid: c15b20c5-a650-44b1-8170-aec2622fed2b
ms:mtpsurl: https://technet.microsoft.com/library/Aa550676(v=AX.60)
ms:contentKeyID: 36059272
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed assets
- asset
- fixed asset
- disposal
- fixed asset disposal
- assets
- asset disposal
- fixed assets disposal
audience: Application User
ms.search.region: Global
---

# About fixed asset disposal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This information explains how to set up transactions for disposing of assets by selling or scrapping them.


> [!NOTE]
> <P>In cumulative update 7 or later for Microsoft Dynamics AX 2012, if the <STRONG>Public Sector</STRONG> configuration key is selected, you can dispose of more than one fixed asset at the same time.</P>



In the **Fixed asset posting profiles** form, on the **Ledger accounts** FastTab, select **Disposal - sale** and **Disposal - scrap** to set up postings to the ledger.

For both transaction types, the ledger account is credited for the disposal value of the fixed asset. The debit is posted to an offset account, which might be, for example, a bank account. If a fixed asset is sold to a customer, the customer account is used instead of the offset account.

Click **Disposal** and then click **Sale** or **Scrap**, and then set up detailed accounts to reverse the net book value of the fixed asset. You can also enter information in the **Post value** and **Sales value type** fields in the **Disposal parameters** form.

The disposal transaction for an asset in a low-value pool reduces the net book value of the low-value pool by the disposed amount only. However, when the sale of an asset is exceeds the net book value of the low-value pool, the net book value is reduced to zero.

## See also

[Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md)

[Post fixed asset journals](post-fixed-asset-journals.md)

  


