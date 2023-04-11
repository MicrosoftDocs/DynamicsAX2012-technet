---
title: Add a table constraint to a component
TOCTitle: Add a table constraint to a component
ms:assetid: 69736dc3-59fe-4cae-8b78-d318cbbf1491
ms:mtpsurl: https://technet.microsoft.com/library/Hh597118(v=AX.60)
ms:contentKeyID: 39519167
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- component
- attribute
- configure
- constraint
- attribute type
- product configuration model
- table constraint
audience: Application User
ms.search.region: Global
---

# Add a table constraint to a component 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must create table constraints before you add them to components. You can view or create table constraints on the **Product configuration models** list page. To do so, click **Table constraints** on the **Action Pane**. You can also set up table constraints on the **Constraints** FastTab in the **Constraint-based product configuration model details** form. To do so, click **Maintain table constraints**.

For more information, see [Create a table constraint](create-a-table-constraint.md).

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select the product configuration model that contains the component to which you want to add a table constraint, and then, on the **Action Pane**, click **Edit**.

3.  In the **Constraint-based product configuration model details** form, select the component in the tree, expand the **Constraints** FastTab, and then click **Add**.

4.  In the **Constraint** field, select **Table constraint**, and then click **Create**.

5.  In the **Name** field, enter a name. Use Microsoft Solver Foundation syntax for the table constraint.

6.  In the **Description** field, enter a description of the constraint.

7.  In the **Table constraint definition** field, click the arrow.

8.  In the **Table constraint attachment** dialog box, in the **Table constraint name** field, select the table constraint to add to the component.

9.  For each attribute type in the **Column name** column, specify the combinations to allow by selecting the attribute in the **Attribute name** column.

## See also

[About system-defined and user-defined table constraints](about-system-defined-and-user-defined-table-constraints.md)

[Create a table constraint](create-a-table-constraint.md)

[About product configuration models](about-product-configuration-models.md)

[About reusing configurations](about-reusing-configurations.md)

  


