---
title: Process assets created from Accounts payable
TOCTitle: Process assets created from Accounts payable
ms:assetid: 6ffa9ac0-448b-4de3-ab66-576daca765b9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231824(v=AX.60)
ms:contentKeyID: 36058052
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accounts payable assets
- AP assets
- assets Accounts payable
audience: Application User
ms.search.region: Global
---

# Process assets created from Accounts payable 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There are four methods for integrating Fixed assets and Accounts payable:

1.  Manually create a fixed asset record in Fixed assets before you add the fixed asset number to the line in the purchase order or invoice. Post an acquisition transaction for the asset when you post the invoice. This is the default method.

2.  Manually create a fixed asset record in Fixed assets before you add the fixed asset number to the line in the purchase order or invoice. Do not post an acquisition transaction for the asset when you post the invoice.

3.  Automatically create a fixed asset record when you post the product receipt or invoice that has the **Create asset during product receipt or invoice posting** check box selected in the **Fixed assets parameters** form. Post an acquisition transaction for the asset when you post the invoice.

4.  Automatically create a fixed asset record when you post the product receipt or invoice that has the **Create asset during product receipt or invoice posting** check box selected in the **Fixed assets parameters** form. Do not post an acquisition transaction for the asset when you post the invoice.

For more information, see [About assets acquired through procurement](about-assets-acquired-through-procurement.md).

This information discusses how to post acquisition and acquisition adjustment transactions from Fixed assets, which is useful if you do not post an acquisition transaction for the asset when you post the invoice. If you use the first or third integration method, you do not have to follow these steps because an acquisition transaction is posted from Accounts payable.

## Process assets using acquisition or acquisition adjustment proposals

1.  Open a proposal form to create acquisition or acquisition adjustment transactions for fixed assets that are created from Accounts payable.
    
      - To create acquisition transactions, open the **Acquisition proposal** form. (Click **Fixed assets** \> **Journals** \> **Fixed assets**. Click **Lines**, and then click **Proposals** \> **Acquisition proposal**.)
    
      - To create acquisition adjustment transactions, open the **Acquisition adjustment proposal** form. (Click **Fixed assets** \> **Journals** \> **Fixed assets**. Click **Lines**, and then click **Proposals** \> **Acquisition adjustment proposal**.)

2.  Click **Select**.

3.  Enter query criteria to select assets that were invoiced.

4.  Click **OK** to create acquisition or acquisition adjustment transactions that you can post for the fixed assets.

## See also

[Post fixed asset journals](post-fixed-asset-journals.md)

[Acquisition proposal (form)](https://technet.microsoft.com/en-us/library/aa575857\(v=ax.60\))

[Acquisition adjustment proposal (form)](https://technet.microsoft.com/en-us/library/hh209549\(v=ax.60\))

[About assets acquired through procurement](about-assets-acquired-through-procurement.md)

  


