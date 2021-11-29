---
title: Create an Advanced condition
TOCTitle: Create an Advanced condition
ms:assetid: b1c48dfe-4c70-467c-8680-8aff8ef9b0e5
ms:mtpsurl: https://technet.microsoft.com/library/Aa498651(v=AX.60)
ms:contentKeyID: 36059055
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create an Advanced condition 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Advanced conditions are intended for more complex expressions. They are similar to Simple conditions, but offer the option to use calculations.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**. Select a product model. On the **Action Pane**, click the **Models** tab. In the **Modify** group \> **Open** \> **Validation**.

2.  In the lower pane, click the **Condition** tab.

3.  Press CTRL+N to create a new condition.

4.  Select **Advanced** in the **Type** field.

5.  In the **Advanced condition** field group, press CTRL+N to create a new line.

6.  In the **Type** field, select whether you want the current line to contain a fixed value or a variable.

7.  In the **Text** field, type the variable name or value that will be used in the condition.

8.  If you selected **Value** in the **Type** field and it belongs to the array group, you can specify its number in the group in the **Index** field.

9.  Select an operator for the current line in the **Operator** field.

10. Repeat steps 5 through 9 to add lines to the advanced expression.

11. Click the **Message** tab to create a message that will be displayed if the condition is true. Select the language in which you will write the message and then type the message text.

  


