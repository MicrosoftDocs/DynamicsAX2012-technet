---
title: Set up cycle counting thresholds and plans to perform cycle counting
TOCTitle: Set up cycle counting thresholds and plans to perform cycle counting
ms:assetid: e5a0d390-8500-4ed3-a58a-eec59d680268
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553209(v=AX.60)
ms:contentKeyID: 62200175
ms.date: 05/27/2015
mtps_version: v=AX.60
f1_keywords:
- mobile device
- Forms.WHSCycleCountPlan
- Forms.WHSCycleCountThreshold
- MsDynAx060.Forms.WHSCycleCountPlan
- MsDynAx060.Forms.WHSCycleCountThreshold
- cycle count grouping
- cycle counting plan
- cycle counting work
- mobile device menu item
- cycle counting threshold
---

# Set up cycle counting thresholds and plans to perform cycle counting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Cycle counting is a warehouse process that you can use to audit on-hand inventory items. This topic explains how to set up cycle counting thresholds and cycle counting plans that you can use to create a cycle counting work. A cycle counting threshold indicates the quantity or percentage limit of inventory items. Cycle counting work is automatically created when the threshold limit is reached. A cycle counting plan is set up to create cycle counting work immediately or periodically. When counting work is created it contains the information about which location to count as part of the counting work line. The on-hand inventory associated with this location is not blocked and is therefore available for reservation and outbound processing even though open counting work exists.

After you create cycle counting work, you must use a mobile device to process cycle counting at a warehouse location. For more information, see [Perform cycle counting in a warehouse location](perform-cycle-counting-in-a-warehouse-location.md).

## Set up threshold for items in a location

Use the **Cycle count thresholds** form to set up cycle counting threshold for items, locations, or both items and locations.

To set up threshold for items in a location, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Cycle counting** \> **Cycle count thresholds**.

2.  Click **New** to set up threshold for items in a location.

3.  Enter an identifier (ID) and a description for the cycle counting threshold.

4.  Enter the threshold quantity and select the unit for the items in a warehouse location. Cycle counting work is created when this threshold is reached.
    

    > [!NOTE]
    > <P>To create cycle counting work that is based on the specified threshold, you must select <STRONG>Quantity</STRONG> in the <STRONG>Cycle counting threshold type</STRONG> field.</P>



5.  In the **Capacity threshold based on percentage** field, enter the threshold percentage for items in a warehouse location. Cycle counting work is created when this threshold is reached.
    

    > [!NOTE]
    > <P>To create cycle counting work that is based on the specified threshold, you must select <STRONG>Percentage</STRONG> in the <STRONG>Cycle counting threshold type</STRONG> field.</P>



6.  Select the **Process cycle counting immediately** check box to initiate the cycle counting as soon as the item quantity reaches the threshold.

7.  In the **Days between cycle counting** field, enter the number of days before a warehouse location is counted again. You can enter a value of zero in this field if you want to create cycle counting work according to the threshold, regardless of when the location was cycle counted.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Process cycle counting immediately</STRONG> check box and specify a value in the <STRONG>Days between cycle counting</STRONG> field, such as 5, the next cycle counting work will be created five days after the last cycle counting work was processed.</P>



8.  Optional: Select the work pool ID for which the cycle counting threshold is assigned. For more information, see [Set up a work pool](set-up-a-work-pool.md).

9.  Optional: Click **Select items** to specify the item criteria for which the threshold is set. Click **OK**.

10. Optional: Click **Select locations** to specify the location criteria for which the threshold is set. Click **OK**.

## Set up cycle counting plans

Use the **Cycle count plans** form to set up a cycle counting plan for items, locations, or both items and locations.

To set up cycle counting plans, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Cycle counting** \> **Cycle count plans**.

2.  Click **New** to set up a cycle counting plan.

3.  Enter an ID and a description for the cycle counting plan.

4.  Optional: Select the work pool ID for which the cycle counting plan is assigned. For more information, see [Set up a work pool](set-up-a-work-pool.md).

5.  In the **Maximum number of cycle counts** field, enter the maximum number of cycle counting work that is created by a cycle counting plan for items in different locations. For example, if an item is available in three different locations in a warehouse, specify two as the **Maximum number of cycle counts**. When you run the cycle counting plan, it will create two cycle counting work for the two locations in which the items are present.

6.  In the **Days between cycle counting** field, enter the number of days before a warehouse location is counted again. You can enter a value of zero in this field to create cycle counting work according to the cycle counting plan, regardless of when the location was cycle counted.
    

    > [!NOTE]
    > <P>Cycle counting work for a location is created based on the value specified in the <STRONG>Days between cycle counting</STRONG> field. For example, if the value specified in <STRONG>Days between cycle counting</STRONG> field is 5, cycle counting work will be created every five days. However, if cycle counting work is processed on day three, the next cycle counting work will be created five days after the last cycle counting was processed, on day eight.</P>



7.  Optional: Click **Select items** to specify the item criteria for which the cycle counting plan is set. Click **OK**.

8.  Optional: Click **Select locations** to specify the location criteria for which the cycle counting plan is set. Click **OK**.

9.  Click **Process cycle counting plan** to run the cycle counting plan at any time or as a scheduled batch job.
    

    > [!NOTE]
    > <P>You can also use the <STRONG>Cycle count scheduling</STRONG> form to run the cycle counting plan in a batch job.</P>



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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

