---
title: (HUN) Set up a posting profile for fixed asset items
TOCTitle: (HUN) Set up a posting profile for fixed asset items
ms:assetid: 5b489565-2b2d-41b7-bcbf-fbbce940e289
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664287(v=AX.60)
ms:contentKeyID: 49385376
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Set up a posting profile for fixed asset items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The cost value of an asset that is moved to inventory must be equal to its current net book value.

In the standard configuration, when you dispose of an asset as scrap, a transaction to inventory is created using the standard cost value defined in the **Invent** table.


> [!NOTE]
> <P>To use the standard configuration, the <STRONG>Fixed assets</STRONG> (CRSEHungary) configuration key must be unselected.</P>



When you use the configuration specific to Hungary, the inventory cost is calculated based on the current net book value of the transferred asset. When you register a transfer in the Inventory to Fixed Assets journal after entering the asset, value model, and item number, the correct cost price is proposed, based on the current net book value of the selected asset.


> [!NOTE]
> <P>To use the Hungary-specific configuration, select the <STRONG>Fixed assets</STRONG> (CRSEHungary) configuration key.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.
    

    > [!NOTE]
    > <P>For more information, see "Inventory Posting (form)" in the Applications and Business Processes Help.</P>



2.  On the **Inventory** tab, select **Receipt**.

3.  In the **Main account** field, select the ledger account for receipt posting to the selected item group.
    

    > [!NOTE]
    > <P>You can set up receipt posting for each item group or for each item.</P>



4.  Click the **Standard cost variance** tab.

5.  In the **Main account** field, select the ledger account for standard cost profit.
    

    > [!NOTE]
    > <P>The difference between the standard cost value of the item and its current net book value is posted to this account when the standard cost is higher than the current net book value. You can set up standard cost profit posting for item groups or for each item.</P>



6.  Press CTRL+S or close the form.

  


