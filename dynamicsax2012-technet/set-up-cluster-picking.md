---
title: Set up cluster picking
TOCTitle: Set up cluster picking
ms:assetid: fa1c3d07-3652-4d5c-b0af-c6e3090064dd
ms:mtpsurl: https://technet.microsoft.com/library/Dn553213(v=AX.60)
ms:contentKeyID: 62200191
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- pick
- mobile device
- Forms.WHSClusterProfile
- outbound
- cluster
- cluster profile
audience: Application User
ms.search.region: Global
---

# Set up cluster picking 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to enable workers to use their mobile devices to group picking work into clusters, so that they can pick items from a single location for multiple work orders at the same time. This is called cluster picking.

## About cluster picking

After work orders are released to the warehouse, the worker can use a mobile device to assign the orders to a cluster. The cluster will organize the picking work for the worker. When a work order is assigned to a cluster, the worker must use cluster picking to perform the picking work for the order. The worker cannot use other picking methods. If a work order is assigned to a cluster by mistake, the worker must break the cluster and then re-create it.

If needed, a worker can pass a cluster to another worker. This changes the cluster status to **Passed**. When the worker uses a mobile device to indicate that the picking and put away work is completed, the shipment or load must be confirmed in the Microsoft Dynamics AX client.

## Set up cluster picking

To enable cluster picking, you must set up the following:

  - **Cluster profiles** – Specify whether to automatically generate cluster IDs, the number of positions to use, when to break clusters, and how to sequence and verify the picking work.

  - **Work templates** – Define how to create the picking work for cluster picking.

  - **Location directives** – Specify where to pick items from, and where to put them.

  - **Mobile device menu items** – Configure a mobile device menu item to use existing work that is directed by cluster picking. You must then add the menu item to a mobile device menu so that it is displayed on mobile devices.

  - **Warehouse management parameters** – Specify the number sequence to use if you want to generate identifiers for clusters.

## Set up a cluster profile

To set up a cluster profile, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Cluster profiles**.

2.  Click **New** to create a new profile.

3.  On the **General** FastTab, in the **Cluster profile ID** and **Name** fields, enter a unique identifier and a name for the profile.

4.  In the **Setup** field group, select from the following options.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Generate cluster ID</strong></p></td>
    <td><p>Select this check box to automatically create identifiers for clusters. If you do not select this check box, you must scan the license plate ID to register the cluster.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you want to enable workers to pass a cluster to another worker, you must create a mobile device menu item that does not generate cluster IDs.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Activate positions</strong></p></td>
    <td><p>Select this check box to automatically generate names for positions based on a numeric or alphabetic system. You select the naming system to use in the <strong>Position name</strong> field. The numeric naming system creates names as 1, 2, 3, and so on. The alphabetic system creates names as A, B, C, and so on.</p>
    <p>If this check box is cleared, the license plate ID for the position is used.</p>
    <div class="alert">

    > [!TIP]
    > <P>Positions represent containers, such as cartons or plastic bins on a cart, and are assigned to work orders. You use positions to separate items for each order during picking.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Number of positions</strong></p></td>
    <td><p>Specify the number of positions to use when picking work is generated.</p>
    <p>If you automatically generate identifiers for positions, this is the number of identifiers that will be created.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Position name</strong></p></td>
    <td><p>If you use positions, specify if you want to use numbers or letters to automatically generate names for positions. If you select <strong>Numeric</strong>, the position names are 1, 2, 3, and so on. If you select <strong>Alpha</strong>, the position names are A, B, C, and so on.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Break cluster at</strong></p></td>
    <td><p>Select the action that will break up the cluster. You can break a cluster when either the picking or put away work is completed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Sort verification type</strong></p></td>
    <td><p>Specify if you must verify that items were put into the correct position, and if you must scan the license plate label or the position to perform the verification.</p></td>
    </tr>
    </tbody>
    </table>


5.  Click **Set up cluster** to open the **Cluster sorting** form, where you can set up sorting criteria for the cluster. The sorting criteria control the order in which the worker will perform the picking work. For example, if you select the **WMSLocationId** field, the work will be sorted by location. You can add as many criteria as needed.

6.  Click **New** to create a new line of criteria for the cluster sorting.

7.  In the **Sequence number** field, ether a number to define the order in which Microsoft Dynamics AX will process the sorting criteria.

8.  In the **Field name** field, select the field that will determine the sorting.

9.  In the **Sorting** field, select one of the following.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Ascending</strong></p></td>
    <td><p>Picking work is sequenced in an ascending order based on the sorting criteria.</p>
    <p>For example, if you use the <strong>WMSLocationId</strong> field as sorting criteria, and your location IDs are 1, 2, 3, and 4, you will pick from location 4 first.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Descending</strong></p></td>
    <td><p>Picking work is sequenced in a descending order based on the sorting criteria.</p>
    <p>For example, if you use the <strong>WMSLocationId</strong> field as sorting criteria, and your location IDs are 1, 2, 3, and 4, you will pick from location 1 first.</p></td>
    </tr>
    </tbody>
    </table>


## Next step

The next step is to configure a mobile device menu item to use existing work that is directed by cluster picking, and assign a cluster profile to the menu item. You must add the menu item to a menu that is displayed on a mobile device.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


