---
title: Add all batch attributes to an item for a customer
TOCTitle: Add all batch attributes to an item for a customer
ms:assetid: 6879d6ae-2aee-49be-85f9-6a0dc0453582
ms:mtpsurl: https://technet.microsoft.com/library/Hh242603(v=AX.60)
ms:contentKeyID: 36057957
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add all batch attributes to an item for a customer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to add all batch attributes to an item for a customer.


> [!IMPORTANT]
> <P>Before you can add all batch attributes to an item for a specific customer, you must first add all batch attributes to the item. For more information, see <A href="add-all-batch-attributes-to-an-item.md">Add all batch attributes to an item</A>.</P>



1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the item.
    

    > [!NOTE]
    > <P>The item you select must be batch controlled. An item is batch controlled if the <STRONG>Batch number</STRONG> field is set to <STRONG>Active</STRONG> for the item's Tracking dimension group.</P>



3.  On the **Action Pane**, on the **Manage inventory** tab, in the **Batch attributes** group, click **Customer specific**.

4.  Press CTRL+N to add a new batch attribute line.

5.  In the **Attribute code** field, select **All**.
    

    > [!NOTE]
    > <P>When you select the attribute code <STRONG>All</STRONG>, the <STRONG>Attribute relation</STRONG> field is not available. The system assumes that all current attributes apply and automatically assigns them to the item for this customer.</P>



6.  In the **Account code** field, select **Table**.

7.  In the **Account selection** field, select the customer’s account.

## See also

[About batch attributes](about-batch-attributes.md)

[Customer specific (form)](https://technet.microsoft.com/library/hh209393\(v=ax.60\))

  


