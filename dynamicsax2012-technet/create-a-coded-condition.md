---
title: Create a Coded condition
TOCTitle: Create a Coded condition
ms:assetid: 7ee19c86-2a39-42e5-b180-341d73f0c4de
ms:mtpsurl: https://technet.microsoft.com/library/Aa571538(v=AX.60)
ms:contentKeyID: 36058323
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a Coded condition 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Coded conditions are written in X++ code. In the **Parameters** field group, variables that can be used in the code are selected. The code is expected to return a Boolean operator. If the code returns TRUE, a configuration is invalid.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**. Select a product model. On the **Action Pane**, click the **Models** tab. In the **Modify** group, click **Open** \> **Validation**.

2.  In the lower pane, click the **Condition** tab.

3.  Press CTRL+N to create a new condition.

4.  In the **Type** field, select **Code**.

5.  In the **Parameters** field group, press CTRL+N to select the variable to use to create the condition.

6.  If the selected variable belongs to the array group, you can specify its index in the group in the **Index** field.

7.  In the **Coded condition** field group, write the X++ code.

8.  Click the **Message** tab to create a message that will appear if the condition is true. Select the language that you will write the message in, and then type the message text.

  


