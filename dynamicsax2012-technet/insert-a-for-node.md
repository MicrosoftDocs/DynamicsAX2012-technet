---
title: Insert a FOR node
TOCTitle: Insert a FOR node
ms:assetid: 7899933c-5ba1-41b5-a1b3-f6e93c42e6be
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550050(v=AX.60)
ms:contentKeyID: 36058227
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Insert a FOR node 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The FOR node repeats a set of actions until a specific condition becomes false. A control structure of this kind is frequently called a loop.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Double-click a product model. From the **Product models** form, click the **Product model** button.

3.  In the lower pane, right-click the **Modeling tree** node. Select **New** and then select **FOR node**.
    
    A new node is added to the bottom of the modeling tree. To insert a node into a particular position in the tree, drag it from the node list displayed on the left.

4.  In the **Description** field, enter a description to describe what the FOR loop does.

5.  In the **Initialization** field, the control variable for the loop is initialized to its value when loop execution starts.
    
    The control variable must be one of the variables defined for the current product model. For example, if the name for the control variable is Counter, the initialization could consist in making the counter equal to the value 1: Counter = 1.

6.  In the **Step** field, specify an action that should be performed on the control variable one time for each loop iteration. The action could consist of adding 1 to the value of the control variable: Counter = counter + 1.

7.  In the **Expression** field, specify—in the form of a logical condition—the state required for the control variable so that the loop will continue to run.
    
    The condition might be that the control variable should be less than or equal to another variable, such as: Counter \<= number\_of\_doors. Make sure that the control variable does, in fact, make the condition false at some point. Otherwise, the FOR node, and therefore the whole product configuration, will continue to run interminably.

## See also

[Product models (form)](https://technet.microsoft.com/en-us/library/aa572853\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

