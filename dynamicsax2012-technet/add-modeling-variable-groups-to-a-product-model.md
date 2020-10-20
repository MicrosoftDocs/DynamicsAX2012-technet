---
title: Add modeling variable groups to a product model
TOCTitle: Add modeling variable groups to a product model
ms:assetid: eadd0a12-a188-46e2-baa5-26727007030e
ms:mtpsurl: https://technet.microsoft.com/library/Aa551498(v=AX.60)
ms:contentKeyID: 36059862
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add modeling variable groups to a product model 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

All modeling variables must belong to a variable group because variables that are not members of a variable group will not appear in the user dialog box.

The variable groups can be grouped, that is, arranged in a hierarchy of groups and subgroups.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



## Add variable groups to a product model and group them

1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Select a product model. On the **Action Pane**, click the **Models** tab. In the **Modify** group, click **Open**.

3.  Select the **Tree** tab in the lower pane.

4.  Double-click **Insert default route**.

5.  To attach modeling variable groups to a product model, in the upper pain, click **Grouping**.

6.  Press CTRL+N to create a new line.

7.  Select the variable group in the **Variable group** field.

8.  Use the **Navigate up** and **Navigate down** buttons to create a hierarchy of variable groups. You can also do this from the **Tree** tab by using the drag-and-drop feature.
    

    > [!NOTE]
    > <P>When you click <STRONG>Navigate up</STRONG> or <STRONG>Navigate down</STRONG>, you move to another group level. This means that on the <STRONG>Overview</STRONG> tab, you will see only groups that belong to the current level. If there are no groups on the current level, the <STRONG>Overview</STRONG> tab will be empty.</P>



## Show user dialog box as tree structure

1.  By default, a top-level group will appear in the user dialog box as a tab, and a first-level subgroup will appear as a field group on the top-level tab for that group. Click **Product information management** \> **Setup** \> **Product builder** \> **Product builder parameters**.

2.  Select the **Show user dialog box as tree structure** check box. The variable groups then appear as nodes in a hierarchical tree structure.

## See also

[Product models (form)](https://technet.microsoft.com/library/aa572853\(v=ax.60\))

  


