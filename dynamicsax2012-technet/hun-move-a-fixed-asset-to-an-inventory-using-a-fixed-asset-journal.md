---
title: (HUN) Move a fixed asset to an inventory using a fixed asset journal
TOCTitle: (HUN) Move a fixed asset to an inventory using a fixed asset journal
ms:assetid: 46a2441b-cbea-418c-82d9-d44df3120908
ms:mtpsurl: https://technet.microsoft.com/library/JJ664270(v=AX.60)
ms:contentKeyID: 49385359
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Move a fixed asset to an inventory using a fixed asset journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Normally, the inventory value of a fixed asset is calculated based on the cost of the item at purchase. To comply with Hungarian accounting law, when you move a fixed asset to inventory, the inventory value must be equal to the net book value of the fixed asset.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Journals** \> **Inventory to fixed assets**. Click **Lines**.

2.  In the **Fixed asset number** field, select the fixed asset.

3.  In the **Transaction type** field, select **Disposal-scrap**.
    

    > [!NOTE]
    > <P>The cost price is calculated automatically based on the current net book value of the selected asset.</P>



4.  In the **Item number** field, select the item to move the fixed asset to inventory.

5.  In the **Quantity** field, select the quantity of the item.
    

    > [!NOTE]
    > <P>You must use a negative quantity in the <STRONG>Quantity</STRONG> field.</P>



6.  Click **Validate** to open the **Check journal** form.

7.  Click **OK** to validate the form.

8.  Click **Post** to post the journal.
    

    > [!NOTE]
    > <P>The fixed asset is then disposed off, and a profit or loss transaction, based on the difference between the standard cost of the fixed asset and its current net book value, is automatically generated.</P>



## See also

[(HUN) Set up a posting profile for a disposal sale](hun-set-up-a-posting-profile-for-a-disposal-sale.md)

  


