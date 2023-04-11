---
title: Add all batch attributes to an item
TOCTitle: Add all batch attributes to an item
ms:assetid: 852ba8e9-e7f4-4e85-bea7-4c09e4ab4e46
ms:mtpsurl: https://technet.microsoft.com/library/Hh209324(v=AX.60)
ms:contentKeyID: 36058402
author: tfehr
ms.author: daxcpft
ms.date: 04/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add all batch attributes to an item 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to add all batch attributes to an item.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the item.
    

    > [!NOTE]
    > <P>The item you select must be batch controlled. An item is batch controlled if the <STRONG>Batch number</STRONG> field is set to <STRONG>Active</STRONG> for the item's Tracking dimension group.</P>



3.  On the **Action Pane**, on the **Manage inventory** tab, in the **Batch attributes** group, click **Product specific**.

4.  Press CTRL+N to add a new batch attribute line.

5.  In the **Attribute code** field, select **All**.
    

    > [!NOTE]
    > <P>When you select the attribute code <STRONG>All</STRONG>, the <STRONG>Attribute relation</STRONG> field is not available. The system assumes that all current batch attributes apply and automatically assigns them to the item.</P>



## See also

[About batch attributes](about-batch-attributes.md)

[Product specific (form)](https://technet.microsoft.com/library/hh227369\(v=ax.60\))

  


