---
title: (HUN) Generate a pre-acquisition transaction for a low-cost asset
TOCTitle: (HUN) Generate a pre-acquisition transaction for a low-cost asset
ms:assetid: d4018c1d-7f22-4aef-ae71-d6b9d764c046
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733164(v=AX.60)
ms:contentKeyID: 49685132
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Generate a pre-acquisition transaction for a low-cost asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A low-cost asset is a fixed asset for which the acquisition cost does not exceed a predefined amount. Hungarian tax law defines the limit for low-cost assets, which can be depreciated in full immediately.

Use this procedure to generate a pre-acquisition transaction for a low-cost asset. Later, when you acquire the asset, you create an acquisition transaction from the pre-acquisition transaction. Posting the acquisition transaction for a low-cost asset generates the depreciation transaction automatically.

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**. Create the low-cost asset. For more information, see [Create a fixed asset](create-a-fixed-asset.md).

2.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

3.  In the **Name** field, select the journal name that your organization uses for fixed asset acquisitions.

4.  Enter any additional values, and then click the **Lines** button.

5.  In the **Journal voucher** form, in the **Transaction type** field, select **Pre-Acquisition**.

6.  In the **Account** field, select the fixed asset number for the low-cost asset.

7.  In the **Value model** field, select the value model for low-cost assets.

8.  Enter or select any additional values, and then click **Validate** \> **Validate** to check the journal.

9.  If no validation errors appear, click **Post** \> **Post** to post the pre-acquisition transaction.

For information about how to create the acquisition transaction from the pre-acquisition transaction, see [(EEUR) Post the pre-acquisition and acquisition of a fixed asset](eeur-post-the-pre-acquisition-and-acquisition-of-a-fixed-asset.md).

## See also

[Journal voucher - Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620564\(v=ax.60\))

[(HUN) Set up a value limit for low-cost assets](hun-set-up-a-value-limit-for-low-cost-assets.md)

[(HUN) Set up a value model for low-cost assets](hun-set-up-a-value-model-for-low-cost-assets.md)

  


