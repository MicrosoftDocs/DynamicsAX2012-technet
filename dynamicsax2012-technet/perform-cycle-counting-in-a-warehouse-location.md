---
title: Perform cycle counting in a warehouse location
TOCTitle: Perform cycle counting in a warehouse location
ms:assetid: 90301cce-3937-45b8-9690-ffe8abc0ab38
ms:mtpsurl: https://technet.microsoft.com/library/Dn727123(v=AX.60)
ms:contentKeyID: 62383464
author: Khairunj
ms.date: 05/28/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Perform cycle counting in a warehouse location 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Cycle counting is a warehouse process that you can use to audit on-hand inventory items. The following tasks are described in this topic:

  - Create cycle counting work ─ Cycle counting work is created automatically based on threshold parameters for items or by using a cycle counting plan. You can also create cycle counting work manually by using the item or warehouse parameters in the **Cycle count work by item** form or the **Cycle count work by location** form.

  - Process cycle count ─ After you create cycle counting work, you perform the cycle counting work by counting items in a warehouse location and entering the result in Microsoft Dynamics AX by using a mobile device. Alternatively, you can count items in a warehouse location without creating cycle counting work. This process is referred to as spot cycle counting.

  - Resolve a difference in the cycle counted value ─ After a cycle count, any items that have differences in the counted value will have a work status of **Pending review** in the **All work** form. You can resolve these differences in the **Cycle counting transactions** form.

The following illustration shows how to perform cycle counting.

![Process flow for cycle counting](images/Dn727123.Performcyclecountinginawarehouselocation(AX.60).jpg "Process flow for cycle counting")

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Precondition</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Item</p></td>
<td><p>The item must be enabled for warehouse management processes. For more information, see <a href="create-items.md">Create items</a> and <a href="key-tasks-release-products.md">Key tasks: Release products</a>.</p></td>
</tr>
<tr class="even">
<td><p>Warehouse</p></td>
<td><p>The warehouse must be enabled for warehouse management processes.</p>
<p>To enable the warehouse for warehouse management processes, in the <strong>Warehouses</strong> form, select the warehouse, and then select the <strong>Use warehouse management processes</strong> check box.</p>
<p>Additionally, if you want to enable workers to move pallets during a cycle count, on the <strong>Warehouse management</strong> FastTab, select the <strong>Allow pallet moves during cycle counting</strong> check box.</p></td>
</tr>
<tr class="odd">
<td><p>Work pools</p></td>
<td><p>Optional: Create a work pool. For more information, see <a href="set-up-a-work-pool.md">Set up a work pool</a>.</p></td>
</tr>
<tr class="even">
<td><p>Locations</p></td>
<td><p>Enable cycle counting for locations. In the <strong>Location profiles</strong> form, select the <strong>Allow cycle counting</strong> box to allow cycle counting for the warehouse location. For more information, see <a href="set-up-parameters-to-create-a-warehouse-location.md">Set up parameters to create a warehouse location</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Warehouse management parameters</p></td>
<td><p>Set up parameters for cycle counting. In the <strong>Warehouse management parameters</strong> form, specify the default adjustment type code, work class ID, and work priority for cycle counting.</p></td>
</tr>
<tr class="even">
<td><p>Mobile device</p></td>
<td><p>Create a menu item for one of the following methods in the <strong>Mobile device menu items</strong> form:</p>
<ul>
<li><p>User directed cycle counting</p></li>
<li><p>System directed cycle counting</p></li>
<li><p>Cycle count grouping</p></li>
<li><p>Spot cycle counting</p></li>
</ul>
<p>For more information, see Configure mobile devices for warehouse work.</p>
<p>Set up a menu for the mobile device. For more information, see <a href="set-up-mobile-device-menus-to-display-work-or-activities.md">Set up mobile device menus to display work or activities</a>.</p>
<p>Create a work user account and assign a mobile device menu to the work user ID. For more information, see <a href="set-up-mobile-device-user-accounts-for-workers.md">Set up mobile device user accounts for workers</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Related setup task</p></td>
<td><p>Set up a cycle counting plan for a warehouse location. For more information, see <a href="set-up-cycle-counting-thresholds-and-plans-to-perform-cycle-counting.md">Set up cycle counting thresholds and plans to perform cycle counting</a>.</p></td>
</tr>
</tbody>
</table>


## Create cycle counting work based on threshold parameters for items

Cycle counting work can be created when the number of items falls below a certain threshold value. For example, there are 60 items in a location for which the cycle counting threshold quantity is 40. During a sales order transaction, 25 items are picked from the location and put in a staging location. Because the new item count of 35 is less than the threshold quantity, cycle counting work is created automatically for the location. Cycle counting threshold parameters are set up in the **Cycle counting threshold** form. For more information about how to set threshold parameters, see [Set up cycle counting thresholds and plans to perform cycle counting](set-up-cycle-counting-thresholds-and-plans-to-perform-cycle-counting.md).

## Schedule cycle counting work

To schedule cycle counting plans to create cycle counting work immediately or periodically, follow these steps.

1.  Click **Warehouse management** \> **Setup** \> **Cycle counting** \> **Cycle count plans**.

2.  Click **Process cycle counting plan**.

3.  Click **Recurrence** to enter the scheduling information for the batch job.

–or–

1.  Click **Warehouse management** \> **Common** \> **Cycle count scheduling**.

2.  On the **Action Pane**, in the **Maintain** group, click **Schedule plan**.

3.  In the **Cycle counting plan ID** field, select the plan that you want to schedule, and then click **OK**.

## Create cycle counting work manually

To create cycle counting work manually, follow these steps:

1.  **Navigation Path Not Found**
    
    –or–
    
    **Navigation Path Not Found**

2.  On the **General** tab, in the **Invoicing has been completed for load %1.** field, enter the maximum number of cycle counting work IDs that you want to create. For example, if the warehouse manager specifies a value of five, then cycle counting work is created for five locations even if the item is present in 10 different locations.

3.  Optional: Select a work pool ID to which the created cycle counting work IDs are assigned. When a work pool ID is processed for cycle counting, the cycle counting work IDs assigned to this work pool are processed as a group.

4.  Optional: Click **Select** to specify item parameters in the **Cycle count work by item** form, or specify warehouse location parameters in the **Cycle count work by location** form.

5.  On the **Batch** tab, select the **Batch processing** check box to create cycle counting work at set intervals.
    

    > [!NOTE]
    > <P>If the <STRONG>Batch processing</STRONG> check box is cleared, the cycle counting work is created only one time, even if the recurrence details are specified.</P>



## Perform a cycle count using a mobile device


> [!NOTE]
> <P>This procedure is performed by using a mobile device. The information that must be provided on the mobile device varies, depending on how the device is configured. The worker who is performing the cycle count can follow the instructions that are displayed on the mobile device to enter the required information.</P>



There are several methods to process cycle counting work using Microsoft Dynamics AX on a mobile device:

  - User directed ─ The worker can specify a cycle counting work ID that is in the **Open** status.

  - System directed ─ The worker is assigned a cycle counting work ID by Microsoft Dynamics AX.

  - Cycle count grouping ─ The worker can group cycle counting work IDs that are specific to a particular location, zone, or work pool.

  - Spot cycle counting ─ Optional: The worker can count items in a warehouse location at any time, without creating cycle counting work, by entering a location ID.

The following procedure is an example of how you can perform spot cycle counting by using a mobile device:

1.  On the mobile device, select the menu item to process spot cycle counting work.

2.  Register the location which is to be spot cycle counted.

3.  Register and confirm the item number and counted item quantity.
    

    > [!NOTE]
    > <P>The status of the cycle counting work is updated to <STRONG>Pending review</STRONG> or <STRONG>Closed</STRONG> in the <STRONG>All work</STRONG> form, depending on the parameters set in the <STRONG>Work users</STRONG> form. For more information, see <A href="set-up-mobile-device-user-accounts-for-workers.md">Set up mobile device user accounts for workers</A>.</P>



4.  Optional: Repeat step 3 for the remaining items in the location and confirm that there are no additional items available for counting.

## Resolve a cycle counting difference

A cycle counting difference occurs if the **Is a cycle count supervisor** check box is cleared for a work user ID in the following scenarios:

  - The cycle counted value is not in the deviation limits that are specified in the **Maximum percentage limit** or **Maximum quantity limit** fields in the **Work users** form. For example, the on-hand inventory quantity in a location is 50 and the deviation limit for the work user is 10. If the work user enters a value that is not between 40 and 60, a difference occurs.

  - The cycle counted value differs from the on-hand inventory quantity and there are no set deviation limits.

You can adjust differences in the cycle counted value and accept it in the **Cycle counting transactions** form. The modified count of the item quantity can be verified in the **On hand by location** form. The cycle counted value is rejected if the difference cannot be approved.

To accept or reject a cycle counting difference, follow these steps:

1.  Click **Warehouse management** \> **Common** \> **Work** \> **All work**.

2.  Select a cycle counting work ID with the **Work status** as **Pending review**.

3.  On the **Action Pane**, in the **Work** group, click **Cycle counting** to open the **Cycle counting transactions** form.

4.  In the **Counted quantity** field, adjust the cycle counted value. Click **Accept count**.
    
    –or–
    
    Click **Reject count** to reject the cycle counted value.
    

    > [!NOTE]
    > <P>Click <STRONG>Derived Work</STRONG> to view details of the cycle counting work that is created after accepting the difference. Click <STRONG>Source order</STRONG> to view details of the original cycle counting work before accepting the difference.</P>



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

  


