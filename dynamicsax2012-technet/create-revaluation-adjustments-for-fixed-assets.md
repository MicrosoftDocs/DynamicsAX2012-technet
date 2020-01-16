---
title: Create revaluation adjustments for fixed assets
TOCTitle: Create revaluation adjustments for fixed assets
ms:assetid: c46be314-bbdf-4391-82af-9eba64f832e4
ms:mtpsurl: https://technet.microsoft.com/library/Aa550727(v=AX.60)
ms:contentKeyID: 36059293
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- revaluation
- revalue
- revalue fixed assets
- write up adjustment
- write-down adjustment
- write down adjustment
- write-up adjustment
audience: Application User
ms.search.region: Global
---

# Create revaluation adjustments for fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Revaluation changes the value of an asset and can cause either an increase or decrease in the value of an asset. One of the main reasons for the revaluation of an asset is to accurately reflect the fair market price of the asset.

Revaluation, write-up adjustments, and write-down adjustments are all adjustments to the acquisition price.

  - Write-down adjustment – A downward adjustment in the accounting value of an asset. The offset account is usually a profit and loss account. This is the most common adjustment.

  - Write-up adjustment – An upward adjustment in the accounting value of an asset. The offset account is usually a different balance sheet account. This is a less common adjustment.

  - Revaluation – A change in the value of an asset. Revaluation can be used for both write-up and write-down transactions, but is a separate transaction type because revaluation proposals are available in the **Fixed assets** journal.

## Set up postings to ledger accounts

Use the **Fixed asset posting profiles** form to designate the ledger accounts for fixed asset revaluation and adjustments.

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**.

2.  Select a fixed asset posting profile.

3.  On the **Ledger accounts** tab, select a value model.

4.  Select **Revaluation**, **Write up adjustment**, or **Write down adjustment**.

## Set up a revaluation group for a fixed asset

Use the **Revaluation groups** form to set up revaluation for a fixed asset.


> [!NOTE]
> <P>(ESP) This form is available only to legal entities whose primary address is in Spain.</P>



1.  Click **Fixed assets** \> **Setup** \> **Revaluation groups**.

2.  Select a revaluation group.

3.  On the **Factor** tab, click **Add**.

4.  Select a date and enter a factor. The factor and the acquisition price determine the revaluation proposal for the fixed asset. For more information, see [(ESP) Revaluation groups (form)](https://technet.microsoft.com/library/aa588676\(v=ax.60\)).

## See also

[Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md)

  


