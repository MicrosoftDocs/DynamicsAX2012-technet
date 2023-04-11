---
title: Add a batch attribute group to an item
TOCTitle: Add a batch attribute group to an item
ms:assetid: 8d5f573c-58a7-41c9-b058-06efe82856ae
ms:mtpsurl: https://technet.microsoft.com/library/Hh209353(v=AX.60)
ms:contentKeyID: 36058496
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add a batch attribute group to an item 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to add a batch attribute group to an item. When you assign a group of attributes to an item, all of the attributes included in the group apply to the item. Any changes that you make to the attributes in the group apply to all items that use that group.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the item.
    

    > [!NOTE]
    > <P>The item that you select must be batch controlled. An item is batch controlled if the <STRONG>Batch number</STRONG> field is set to <STRONG>Active</STRONG> for the item's tracking dimension group.</P>



3.  On the **Action Pane**, on the **Manage inventory** tab, in the **Batch attributes** group, click **Product specific**.

4.  Press CTRL+N to add a new batch attribute group.

5.  In the **Attribute code** field, select **Group**.

6.  In the **Attribute relation** field, select the batch attribute group that you want to add to the item.

## See also

[About batch attributes](about-batch-attributes.md)

[Product specific (form)](https://technet.microsoft.com/library/hh227369\(v=ax.60\))

  


