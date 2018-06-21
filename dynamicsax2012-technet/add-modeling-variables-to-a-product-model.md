---
title: Add modeling variables to a product model
TOCTitle: Add modeling variables to a product model
ms:assetid: 1114ca01-2c4e-4138-acaa-59bfbd687254
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496564(v=AX.60)
ms:contentKeyID: 36676368
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Add modeling variables to a product model [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

All modeling variables must belong to a variable group. You can add modeling variables to a product model only after you attach variable groups. Click **Grouping** on the **Product model** form.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Select a product model. On the **Action Pane** click **Open**.

3.  In the upper pane, press CTRL+N to create a new line.

4.  In the **Variable group** field, select the variable group that the modeling variable will belong to.
    

    > [!NOTE]
    > <P>If there are no variable groups to select from, you must create a variable group in the <STRONG>Variable group</STRONG> form.</P>



5.  The field **Print** is used to control whether the product model variable will be printed on business documentation.

6.  The **Priority** field is used to indicate how the variables are sorted when they are presented. Enter the number of the variable that is created. If no priority is entered, the modeling variables appear to the user in the order in which they are attached to the product model.

7.  Select the modeling variable that you want to attach to the current product model in the **Variable** field.

8.  You can assign a default value to the variable in the **Default** field.

9.  Select the **Inherit** check box if you want the value of that variable to be inherited from a parent product model during item configuration.

10. Select the **Return value** check box if you want the value of that variable to be returned to a parent product model during item configuration.

11. Use the **Field properties** field to select whether the modeling variable is visible, editable, hidden, or mandatory in the form. If it is mandatory, the user must fill in a value for the variable during item configuration.

12. Select the **Include in reuse** check box if you want the variable to be included in the search criteria when the system performs a search for similar configurations.
    

    > [!NOTE]
    > <P>This check box is visible only if the <STRONG>Reuse configurations</STRONG> field in the <STRONG>Product builder parameters</STRONG> form is set to <STRONG>Prompt</STRONG> or <STRONG>Always</STRONG>.</P>



## See also

[About item modeling variables](about-item-modeling-variables.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

