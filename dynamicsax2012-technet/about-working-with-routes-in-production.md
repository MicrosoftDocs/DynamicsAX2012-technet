---
title: About working with routes in production
TOCTitle: About working with production routes
ms:assetid: aee89107-3c08-4184-978d-dd0e0b35da61
ms:mtpsurl: https://technet.microsoft.com/library/Aa498604(v=AX.60)
ms:contentKeyID: 36687960
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- operation
- routes
- production
- operations
- route
audience: Application User
ms.search.region: Global
---

# About working with routes in production 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Routes and route versions are required by the production functionality in Microsoft Dynamics AX. A route contains the set of operations that are required to produce a product or an item. This includes the sequence of operations, the site where the production occurs, the resource requirements that are involved, and the standard times that are required to set up and run the operations. The information that is required for scheduling the actual production is contained in the operations.

## Route versions and production routes

A route version connects an item to a route. You can assign multiple items to a route by using a route version. In addition, you can allow for variations in the production process by creating more than one route version for an item. For example, if the original route is intended for large orders and uses high-capacity machines, you can handle small production runs more economically by creating a route version that uses lower capacity machines.

Production routes are created specifically for production orders. When you create a production order, the system copies the original route and creates a production route that is used to produce the item on the order. You can change, add, or delete information about the production route without affecting the original route.

## Prerequisites

Before you can work with routes in **Production control**, you must set up some information in other modules in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Module</p></th>
<th><p>Information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Organization administration</strong></p></td>
<td><ul>
<li><p>Set up information about your internal organization and organization hierarchies.</p></li>
<li><p>Set up capabilities for resources in the <strong>Resource capabilities</strong> form.</p></li>
<li><p>Optional: Set up resource groups and resources in the <strong>Resource groups</strong> form and <strong>Resources</strong> form. For more information, see <a href="set-up-and-define-resource-groups-for-operations-resources.md">Set up and define resource groups for operations resources</a> and <a href="create-and-maintain-operations-resources.md">Create and maintain operations resources</a>.</p></li>
<li><p>Optional: Set up calendars in the <strong>Calendars</strong> form. For more information, see <a href="create-working-time-calendars.md">Create working time calendars</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>General ledger</strong></p></td>
<td><p>Set up accounts on the <strong>Main accounts</strong> list page.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inventory and warehouse management</strong></p></td>
<td><p>Set up products on the <strong>Products</strong> list page.</p></td>
</tr>
</tbody>
</table>


After you set up prerequisites, you can set up the following required information in the **Production control** module:

  - **Cost categories** – For more information, see [Create cost categories](create-cost-categories.md).

  - **Route groups** – For more information, see [Create route groups](create-route-groups.md).

  - **Operations** – For more information, see [Set up operations for production](set-up-operations-for-production.md).

  - In addition, you can set up parameters in routes and cost groups in bills of materials.

## See also

[About production setup requirements](about-production-setup-requirements.md)

[Create and update production routes](create-and-update-production-routes.md)

[Create route versions](create-route-versions.md)

[Create route groups](create-route-groups.md)

[Create and update requirements on a route](create-and-update-requirements-on-a-route.md)

[Create or update route operations](create-or-update-route-operations.md)

  


