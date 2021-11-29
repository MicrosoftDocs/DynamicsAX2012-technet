---
title: Set up a production unit
TOCTitle: Set up a production unit
ms:assetid: f489a832-4014-4d6a-ac42-e79897ed21bb
ms:mtpsurl: https://technet.microsoft.com/library/Gg243284(v=AX.60)
ms:contentKeyID: 36059994
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- production unit
audience: Application User
ms.search.region: Global
---

# Set up a production unit 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A production unit is an administrative unit that is a collection of resource groups. A production unit can contain multiple resource groups, but a resource group can be assigned to only one production unit. A production unit reflects the physical layout of production resources and has no effect on transactions or how they are processed.

You must associate a production unit with a site. You can also assign a picking warehouse and a storage warehouse to a production unit.

You can use a production unit to consolidate and filter production-related data. For example, a shop floor manager can see an overview of the outstanding workload and the available capacity for a particular production unit.


> [!NOTE]
> <P>The Operations resource configuration key must be enabled to carry out these tasks.</P>



## Create a production unit

1.  Click **Production control** \> **Setup** \> **Production** \> **Production units**.

2.  Click **New** on the toolbar, or press CTRL+N to create a new entry.

3.  In the **Production unit** field, enter a unique identifier for the production unit, and in the **Name** field, enter a description.

4.  In the **Site** field, select the site at which the production unit operates.

5.  Click the **General** FastTab.

6.  To assign a picking warehouse to the production unit, in the **Input warehouse** field, select a warehouse. The list displays the warehouses that are assigned to the same site as the production unit.

7.  To assign a storage warehouse to the production unit, in the **Output warehouse** field, select a warehouse. The list displays the warehouses that are assigned to the same site as the production unit.

8.  Save the record.


> [!NOTE]
> <P>On the <STRONG>Hierarchy</STRONG> FastTab, you can expand the tree structure to view all the warehouses that are set up for all sites. After you expand the tree structure, you can collapse it by clicking the <STRONG>Collapse</STRONG> button.</P>



## Assign a resource group to a production unit

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  In the **Site** field, select a site.

3.  On the **General** FastTab, in the **Production unit** field, select a production unit. The drop-down list displays the production units that are associated with the site that you selected in the previous step.

4.  Save the record.

After you create a production unit and assign it to a resource group, you can filter the **Current operations** list page by production unit.


> [!NOTE]
> <P>You can change the production unit that is assigned to a resource group. You can also delete a production unit. However, these changes to the production unit are effective only for new orders that are created after master scheduling is run. If you want to apply the production unit change to existing orders, you must do so manually.</P>



## See also

[Production unit (form)](https://technet.microsoft.com/library/hh208601\(v=ax.60\))

  


