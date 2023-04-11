---
title: (RUS) Set up inventory profile parameters for bailment
TOCTitle: (RUS) Set up inventory profile parameters for bailment
ms:assetid: f232777f-9408-46df-96df-2863ef3f356a
ms:mtpsurl: https://technet.microsoft.com/library/JJ733405(v=AX.60)
ms:contentKeyID: 49685272
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up inventory profile parameters for bailment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up an inventory profile and parameters for an item that is stored in a warehouse during bailment.

1.  Click **Inventory management** \> **Setup** \> **Dimensions** \> **Inventory profiles**.

2.  Press CTRL+N to create a new inventory profile for an item.

3.  In the **Inventory profile** field, select a name for the inventory profile.

4.  In the **Name** field, enter a description for the inventory profile.

5.  Click the **General** FastTab.

6.  In the **Kind of activity** field, select **Bailee**. The **Prohibit cost adjustment**, **Prohibit misc. charges on customer/vendor**, **Initialize dimension**, **Control dimension in purchase order**, and **Control dimension in sales order** check boxes are selected.

7.  Select the **Split customer invoice** check box to split the sales order based on the site, delivery information, posting profile, kind of activity, and inventory owner for bailment. In the **Tax receivable processing** and **Tax payable processing** fields, **Do not calculate** is selected.

8.  Select the **Don’t match** check box to prevent automatic matching of on-hand inventory between this inventory profile and a compatible inventory profile.

9.  Click the **Matching priority** FastTab.

10. Click **Up** or **Down** to change the order of the inventory profile.

## See also

[(RUS) Inventory profiles (form)](https://technet.microsoft.com/library/jj733188\(v=ax.60\))

  


