---
title: Create a Simple condition
TOCTitle: Create a Simple condition
ms:assetid: 1e7e6cba-ec54-4111-a448-37f24a2632b0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496776(v=AX.60)
ms:contentKeyID: 36056146
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a Simple condition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Simple conditions can be used to create simple constraints. For example, you could set up a condition to indicate that a user cannot select a red lamp shade while configuring a lamp, if he or she has selected plastic for the material. If the user selects a red shade, 'Plastic' would not be available for material. Simple conditions consist of a field compared with a value. Simple conditions can consist of one or more lines. In that case, the lines are combined by a logical OR.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



Array variables can be referred to either by number or without number. If used without number, the expression is applied to any index value.

1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**. Select a product model. On the **Action Pane**, click the **Models** tab. In the **Modify** group, click **Open** \> **Validation**.

2.  In the lower pane, click the **Condition** tab.

3.  Press CTRL+N to create a new condition.

4.  Select **Simple** in the **Type** field.

5.  In the **Simple condition** field group, press CTRL+N.

6.  In the **Variable** field, select the variable that will be used for the condition.

7.  If the selected variable belongs to the array group, type its number in the **Index** field.

8.  In the **Operator** field, select an operator for the current line.

9.  In the **Type**, select whether the variable specified in the **Variable** field will receive a specific value or will be calculated according to a formula.
    
      - If you selected **Value**, specify it in the **Value** field.
    
      - If you selected **Calculated**, click **Calculated** to create a formula.

10. Click the **Message** tab to create a message that will appear if the condition is TRUE. Select the language that you will write the message in, and then type the message text.

## See also

[Product models (form)](https://technet.microsoft.com/en-us/library/aa572853\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

