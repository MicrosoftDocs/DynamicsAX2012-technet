---
title: Set up a route plan and routing guide for freight transportation
TOCTitle: Set up a route plan and routing guide for freight transportation
ms:assetid: a89cb7c7-4fe2-457f-8b9f-b2e8606406a4
ms:mtpsurl: https://technet.microsoft.com/library/Dn553189(v=AX.60)
ms:contentKeyID: 62200133
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSRouteGuide
- MsDynAx060.Forms.TMSRouteGuide
- MsDynAx060.Forms.TMSRoutePlan
- route plan
- destination point
- origin point
- transportation route
- transport freight
- routing guide
audience: Application User
ms.search.region: Global
---

# Set up a route plan and routing guide for freight transportation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up a route plan and a routing guide that you can use for complex transportation processes. Route plans contain route segments that provide information about freight delivery. You must select route plans to set up a routing guide. The routing guide defines the transportation route.

## Set up a route plan

Use the **Route plan** form to set up a route plan. Route plans contain route segments that provide information about the shipping carrier, carrier service, carrier group, origin and destination hubs, mode of transport, and other details pertaining to freight delivery.

1.  Click **Transportation management** \> **Setup** \> **Routing** \> **Route plan**.

2.  Click **New** to create a new route plan.

3.  Enter a unique identifier and a name for the route plan.

4.  On the **Details** FastTab, click **New** to create line details for the route plan.

5.  In the **Sequence** field, enter the order in which the route segments in the route plan are used.

6.  Enter a name for the route segment.

7.  In the **Origin hub** and **Destination hub** fields, select the starting and ending hubs for the route segment.

8.  Optional: In the **Person in charge for payment** field, select the party that is responsible for paying for the freight services.

9.  Optional: Select the vendor and the invoice account details for the vendor who will transport the freight.

10. Optional: Click **Create spot rates** to create spot rates for route segments.

11. To update the route hub configurations, click **Edit hubs** to open the **Route hub configuration** form.

## Set up a routing guide

Use the **Routing guide** form to set up a routing guide and select route plans for it.

1.  Click **Transportation management** \> **Setup** \> **Routing** \> **Routing guide**.

2.  Click **New** to create a new route guide.

3.  Enter a unique identifier and a name for the routing guide.

4.  On the **Information** FastTab, in the **Direction** field, select the direction for loads.

5.  Select the **Active** check box to enable the routing guide.

6.  Optional: In the **Equipment** field, select the equipment that you want to use for the load.

7.  Optional: Select the **Residential** check box to determine the surcharge rate for remote deliveries.

8.  Optional: In the **Effective start date and time** and **Effective end date and time** fields, select the effective start date and time and end date and time for the route plan.

9.  Optional: On the **Accounts** FastTab, select the customer and the account number for the customer invoice.

10. Optional: On the **Origin** and **Destination** FastTabs, select the settings for origin and destination hubs.

11. Optional: On the **Limits** FastTab, enter the limits for the container volume, the container weight, and the number of containers.

12. On the **Result** FastTab, select unique IDs for the shipping carrier, carrier service, and carrier group.

13. In the **Route plan** field, select a route plan for the routing guide.

## Next step

[Set up transportation constraints for routes](set-up-transportation-constraints-for-routes.md)

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

  


