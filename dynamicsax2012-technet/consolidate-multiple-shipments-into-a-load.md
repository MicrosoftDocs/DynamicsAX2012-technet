---
title: Consolidate multiple shipments into a load
TOCTitle: Consolidate multiple shipments into a load
ms:assetid: 1efe844c-e55c-492b-bd6e-0ea0d88cf965
ms:mtpsurl: https://technet.microsoft.com/library/Dn770230(v=AX.60)
ms:contentKeyID: 62583045
author: Khairunj
ms.date: 11/13/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Consolidate multiple shipments into a load 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to consolidate multiple shipments into one load. You can consolidate multiple shipments for sales orders, purchase orders, or transfer orders based on one of the following scenarios:

  - Shipments to different destinations in the same route that use the same hub or hubs.

  - Shipments that originate from the same warehouse and use the same route.

  - Shipments to the same destination.


> [!NOTE]
> <P>If you are running Microsoft Dynamics AX 2012 R3 Cumulative Update 8, you can use the <STRONG>Load building workbench</STRONG> to create proposed loads based on load building strategies. Load building strategies contain logic that will find sales order lines that match the criteria that you specify in the strategy, and propose loads according to the criteria. You can then examine the contents of the loads and make adjustments, and then build loads based on the proposed loads. Additionally, you can schedule a batch job to automate the process of building loads based on load building strategies. For more information, see <A href="automate-the-process-of-building-loads.md">Automate the process of building loads</A>.</P>



## This task is part of a bigger process

The following illustration shows how to consolidate shipments into a load while planning an outbound load for shipping.

For an overview of the process, see [Business process: Planning and processing outbound loads for shipping](business-process-planning-and-processing-outbound-loads-for-shipping.md).

![Business process flow for outbound loads](images/Dn770230.Planningandprocessingoutboundloads(AX.60).jpg "Business process flow for outbound loads")

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
<li><p>Set up one or more warehouses in Microsoft Dynamics AX. For more information, see <a href="create-warehouses.md">Create warehouses</a>.</p></li>
<li><p>Set up a hub. For more information, see “Set up a hub master” in <a href="set-up-accessorial-charges-for-a-shipping-carrier.md">Set up accessorial charges for a shipping carrier</a>.</p></li>
<li><p>In the <strong>Transportation management parameters</strong> form, on the <strong>In transit planning</strong> FastTab, select the <strong>In transit planning</strong> check box to enable consolidation of shipments.</p></li>
<li><p>Create or modify an outbound load for shipment. For more information, see <a href="create-or-modify-an-outbound-load.md">Create or modify an outbound load</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Consolidate shipments to different destinations on the same route

Use the **Load planning workbench** form to consolidate multiple shipments that are being shipped to different destinations on the same route. For example, two shipments that are created for two different sales orders must ship the items to two different destinations in the same route. Both shipments are sent to a common hub, which is an intermediary location between the outbound dock and the final destinations. When the shipments are at the hub, the transport coordinator consolidates the two shipments into one load to ensure the optimal route for both the shipments.

To consolidate shipments that are being shipped to different destinations, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Load planning workbench**.
    
    –or–
    
    Click **Warehouse management** \> **Common** \> **Load planning workbench**.

2.  On the **Loads** FastTab, select a load line.

3.  On the **Transportation** menu, click **Hub consolidation**.

4.  In the **Override location** form, select an override location type, and select a hub or warehouse location to specify an intermediary location for the shipment.

5.  Click **OK** to create a new transportation request line with the selected location as the source location.

6.  Optional: Repeat steps 2 through 5 to specify other intermediate locations for the shipment.

7.  On the **Supply and demand** FastTab, on the **Transportation request lines** tab, select the lines that share a common hub or warehouse location, to consolidate them.

8.  Click **To new load** to add the selected lines to a new load with a new load template or click **To existing load** to add the selected lines to an existing load.

## Consolidate shipments to the same destination

To consolidate shipments that are being shipped to the same destination, follow these steps:

1.  Click **Transportation management** \> **Common** \> **Shipments** \> **All shipments**.

2.  Select a shipment line for consolidation.

3.  On the **Shipments** tab, in the **Shipments** action group, click **Consolidate shipments** to open the **Shipment consolidation** form.

4.  Select the shipment line that you want to consolidate with the shipment line in the **All shipments** form, and then click **OK**. You can view the consolidated shipment details for the selected shipment line in the lower grid of the **All shipments** form.

5.  Repeat step 4 to consolidate additional shipment lines with the shipment line that is selected in the **All shipments** form.

## Next step

[Plan appointments for a load](plan-appointments-for-a-load.md)

## Related tasks

[Assign a rate and route to a load](assign-a-rate-and-route-to-a-load.md)

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

  


