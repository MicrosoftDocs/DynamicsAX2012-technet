---
title: About the structure of product groups
TOCTitle: About the structure of product groups
ms:assetid: d44c2759-7827-4962-8ada-1b0f590d77cc
ms:mtpsurl: https://technet.microsoft.com/library/Aa551092(v=AX.60)
ms:contentKeyID: 44081046
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product groups
- product group
- structure
audience: Application User
ms.search.region: Global
---

# About the structure of product groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Product groups are used to present items in a way that is suited to the Internet. This topic describes the layout of the **Product groups** form, and how to use the form. (Click **Product information management** \> **Setup** \> **Product catalogs** \> **Product groups**.)

## Product groups in the upper pane

In the upper pane, you create product groups. In the **Type** field, you define the type of group. A product group can have a type of either **Group node** or **Item node**.

The **Group node** type is used to generate the overall structure of the product group. However, the actual items from the inventory list are attached to the **Item node** type. The **Top node** field indicates whether the group node or the item node is a top node. A top node is the highest level in a hierarchy. If a filter icon appears in the **Selection** field, selection criteria for the item node have been defined in the **Select items** form.


> [!TIP]
> <P>To open the <STRONG>Select items</STRONG> form, click <STRONG>Select items</STRONG>. In the <STRONG>Item selection</STRONG> form, click <STRONG>Select</STRONG>.</P>



## Component groups in the lower pane

The information that is displayed in the lower pane varies, depending on whether a group node or an item node is selected in the upper pane. In the upper pane, you typically select a top node that includes the product groups. When you create a top node, you have to add relations in the top node. The top node is usually a group node. Therefore, unless you have only one level, you can create only component groups in the lower pane.

Component groups are product groups that will be included in the group node that is selected in the upper pane. When you add component groups to a group node, you can select only component groups that are available as product groups in the upper pane. These product groups can be either group nodes or item nodes. When relations are created with a product group that is an item node, the layout of the lower pane changes. In the new layout, all items that are attached to the current item node are created.


> [!TIP]
> <P>To add items to the item node, click <STRONG>New</STRONG> or press CTRL+N. Then select the item in the <STRONG>Item group</STRONG> field. You can also add items by clicking <STRONG>Select items</STRONG>.</P>



## Where items and groups belong

In the product group pane in the upper pane, click the **Where-used** tab to see which product group a selected product group belongs to. The hierarchical tree structure shows where the product group belongs. In the tree structure pane at the top of the form, you can view the tree structure. The tree structure displays the current node and all nodes that are under it. By default, the first subordinate level is displayed. You can expand and collapse additional levels by clicking the **+** and **-** symbols next to a node.

## Presentations of the product groups and items

You can attach presentations to product groups and items by clicking a **Presentations** button to open the **Presentations** form. In the **Presentations** form, you can add text and an image to each product group and item. For more information, see [Set up product group and item presentations](set-up-product-group-and-item-presentations.md).


> [!NOTE]
> <P>If you add or change the structure of the product groups and items, make sure that you click <STRONG>Update</STRONG>. Otherwise, the information is not saved to the database.</P>



## See also

[About product groups](about-product-groups.md)

[Product groups (form)](https://technet.microsoft.com/library/aa572041\(v=ax.60\))

  


