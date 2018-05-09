---
title: Create an Action rule
TOCTitle: Create an Action rule
ms:assetid: 755f2f22-7c5a-42d7-ae6f-3cc3a74323f4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550028(v=AX.60)
ms:contentKeyID: 36058170
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create an Action rule 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If rules are of the **Action** type, the **Actions** tab page is available, where you can define actions for true or false conditions.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**. Select a product model. On the **Action Pane**, click the **Models** tab. In the **Modify** group, click **Open** \> **Validation**.

2.  Click the **Condition** tab, and then create the conditions that the actions will be defined for, as described in the [Constraint rule type](constraint-rule-type.md) topic.

3.  Click the **Actions** tab.

4.  In the **Variable** field group, press CTRL+N.

5.  In the **Variable** field, select the variable name.

6.  If the selected variable belongs to the array group, type its number in the **Index** field.

7.  In the **if true** field group, define the actions that will be performed when the condition is true.

8.  Press CTRL+N.

9.  In the **Field properties**, select **Hide**, **Show only**, **Allow edit**, or **Mandatory**.

10. In the **Type** field, specify if the variable selected in the **Variable** field will have a specific value or be calculated according to a formula.
    
      - If you selected **Value**, specify it in the **Value** field.
    
      - If you selected **Calculated**, click **Calculated** to create a formula.

11. Select the **Recalculate** check box if the rules that contain the selected variable should be recalculated.

12. Click the **Up** and **Down** buttons to change the order that the actions will be performed in.

13. In the **if false** field group, complete steps 8–13 to set up the actions that will be performed if the condition is false.

14. Create any messages required on the **Message** tab page. Messages are language specific. Therefore, the label ID must be specified for each message that you create.

## See also

[Product models (form)](https://technet.microsoft.com/en-us/library/aa572853\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

