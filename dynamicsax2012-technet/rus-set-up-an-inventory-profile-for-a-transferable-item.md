---
title: (RUS) Set up an inventory profile for a transferable item
TOCTitle: (RUS) Set up an inventory profile for a transferable item
ms:assetid: aaaa7a29-8fa7-4cb3-8fed-8e47ad4eca86
ms:mtpsurl: https://technet.microsoft.com/library/JJ852150(v=AX.60)
ms:contentKeyID: 50281236
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up an inventory profile for a transferable item 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up an inventory profile for items that are purchased by a legal entity, so that the items can be transferred to the warehouse of the legal entity.

1.  Click **Inventory management** \> **Setup** \> **Dimensions** \> **Inventory profiles**.

2.  Press CTRL+N to create an inventory profile for an item.

3.  In the **Inventory profile** field, select the name of the inventory profile.

4.  In the **Name** field, enter the description of the inventory profile.

5.  On the **Setup** FastTab, in the **Kind of activity** field, select **Basic**.

6.  Select the **Don’t match** check box to prevent on-hand inventory that uses this inventory profile from being matched automatically with a compatible inventory profile.

7.  In the **Kind of inventory** field, select **Purchased items in route**. The **Initialize dimension** and **Control dimension in purchase order** check boxes are selected.
    

    > [!NOTE]
    > <P>The <STRONG>Kind of inventory</STRONG> field is available only when you select <STRONG>Basic</STRONG> in the <STRONG>Kind of activity</STRONG> field.</P>



8.  On the **Matching priority** FastTab, click **Up** or **Down** to change the order of the inventory profile.

## See also

[(RUS) Set up officials for the Counting act INV-6 report](rus-set-up-officials-for-the-counting-act-inv-6-report.md)

[(RUS) Inventory profiles (form)](https://technet.microsoft.com/library/jj733188\(v=ax.60\))

  


