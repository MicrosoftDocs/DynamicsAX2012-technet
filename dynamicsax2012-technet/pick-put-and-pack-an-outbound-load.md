---
title: Pick, put, and pack an outbound load
TOCTitle: Pick, put, and pack an outbound load
ms:assetid: 30305963-f259-49e0-8700-4afdd77bd321
ms:mtpsurl: https://technet.microsoft.com/library/Dn770231(v=AX.60)
ms:contentKeyID: 62583044
author: Khairunj
ms.date: 07/11/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Pick, put, and pack an outbound load 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



You can pick and put items for an outbound load by using Microsoft Dynamics AX on a computer or on a mobile device. This topic explains how you perform this process on a computer. For more information about how to use mobile devices for warehouse work, see [Setting up mobile devices](setting-up-mobile-devices.md).

When you pick a load from a storage location, you can put it in the staging area for packing or put it on the outbound dock for shipping. After the load is moved to the outbound dock, it is loaded into a container for shipping. You can create pick-and-put work by using a wave process. For more information about processing a wave, see [Create, process, and release a wave manually](create-process-and-release-a-wave-manually.md).

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisites</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Preconditions</p></td>
<td><ul>
<li><p>Create a container type, container group, and container build template. For more information, see <a href="set-up-containerization.md">Set up containerization</a>.</p></li>
<li><p>Select a location profile for the packing location in the <strong>Warehouse management parameters</strong> form.</p></li>
<li><p>Set up packing and close container profiles. For more information, see <a href="set-up-packing-and-container-closing-profiles-for-manual-pack-process.md">Set up packing and container closing profiles for manual pack process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Pick and put items for an outbound load

You can pick and put items for an outbound load by using a computer or a mobile device. For more information about how to use mobile devices for warehouse work, see [Setting up mobile devices](setting-up-mobile-devices.md).

To pick and put items for an outbound load on a computer, follow these steps:

1.  Click **Warehouse management** \> **Common** \> **Work** \> **All work**.
    
    –or–
    
    Click **Warehouse management** \> **Common** \> **Work details**.

2.  Select a work ID, and then click **Complete work** to process the pick and put work.

3.  In the **Work completion** form, select a user ID, and then click **Validate work** to validate the work.

4.  Click **Complete work** to complete the work.
    

    > [!NOTE]
    > <P>The work is completed and the work status is updated to <STRONG>Closed</STRONG> in the <STRONG>All work</STRONG> form and the <STRONG>Work</STRONG> form.</P>



## Pack items for an outbound load in a container

To pack items into a container, you must have a container ID. A container ID is created automatically when a wave is processed using the containerization method. For more information about the containerization method, see [Create a wave template](create-a-wave-template.md). After the container ID is specified, the items are packed into a container.

Alternatively, you can specify the container ID manually if it is not created during wave processing. Use the **Pack** form to specify the container ID into which the items are packed.

To pack items into a container, follow these steps:

1.  Click **Warehouse management** \> **Common** \> **Pack**.

2.  In the **Select a packing profile.** form, select a work user ID and packing profile ID. Click **OK**.

3.  In the **Pack** form, enter the license plate ID or shipment ID for the items to be packed. You can view the shipment details on the **Open lines** tab.

4.  Click **New** to add a container.

5.  In the **The ID of the new container.** form, specify a container ID and container type. Click **OK**.
    

    > [!NOTE]
    > <P>The container ID is displayed automatically if <STRONG>Auto</STRONG> is selected in the <STRONG>Container ID mode</STRONG> field in the <STRONG>Packing profiles</STRONG> form.</P>



6.  In the **Pack** form, in the **Pack Item** field group, specify the item number and the quantity of items to be packed. In the lower pane, on the **All lines** tab, you can view the details of the packed items.

7.  Click **Close container** to close the container. The status of the container is updated as **Closed** in the **Containers** form.

8.  Optional: In the **Containers** form, click **Reopen container** to reopen a closed container. Repeat steps 1 through 7 to pack items in the reopened container.

## Next step

[Consolidate multiple shipments into a load](consolidate-multiple-shipments-into-a-load.md)

## Related tasks

[Plan appointments for a load](plan-appointments-for-a-load.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and then select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


