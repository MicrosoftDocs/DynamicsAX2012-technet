---
title: About production terminology
TOCTitle: About production terminology
ms:assetid: aaabc87c-bad3-4b59-bf8d-6f3278af3549
ms:mtpsurl: https://technet.microsoft.com/library/Aa550330(v=AX.60)
ms:contentKeyID: 36058902
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About production terminology 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following terminology is used throughout the **Production** module. Expand to learn more.

## Alternative work centers

Alternative work centers are work centers that can be set up so that the system automatically chooses them when capacity is limited and the primary work center is not available.

## Backward scheduling

Backward scheduling is used to schedule the production as late as possible. This is also known as the pull method, because it is driven by the due date and pulled through the production process. It is scheduled backward from the delivery date required for the production.

## Bill of material (BOM)

A bill of material or BOM is an item that consists of other items. The cost of a BOM is derived from its components, or ingredients, and the cost of producing the item. When production is complete, a BOM is a "finished good" that can be sold. The price of the BOM can be manually assigned or calculated by marking up the costs incurred in making it. Bills of materials can be simple without significant operational costs or complex and require detailed production processes.

  - **Simple BOM** – Lamp – Assembly of lamp and lamp shade.

  - **Complex BOM** – Car – Made up of hundreds of components and BOMs. It is possible to have BOMs within a BOM. This is usually referred to as a sub-assembly or sub-BOM. When a bill of materials has several layers of BOMs nested within it, it is referred to as having multiple layers.
    
    An example of a multi-layer BOM: Carburetor BOM within Engine BOM within Automobile BOM.

  - **Active BOM** – Designation that the current bill of materials version is active and will be used as the valid structure for the BOM lines when the item is processed.

  - **Approved BOM** – Designation that the current BOM version has been approved so that it can be set as active for use.

## Capacity

Capacity is the percentage of company resources available for production.

## Cost estimation

Cost estimation calculates the associated material, route and additional costs for a production order based on the planned production quantity.

## Item consumption

Item consumption transfers the cost of the BOM components, also known as raw materials, to the production order and Work in Process (WIP) accounts. The quantity-on-hand of the component items is reduced. Item consumption can be done automatically or manually by entering a picking list journal. The item consumption can occur during the production process (WIP) or when the finished good is completed.

## Operation

Operations are a step in the production process. Examples of operations are cutting, mixing, painting, assembly.

## Route

Routes are the sequence and length of time it takes operations to produce a bill of materials item. If each item is unique, there might be one route for each inventory item. If not, several items can be attached to the same route.

## Route consumption

Route consumption calculates the cost of a production operation and transfers that cost to the production order and Work in process (WIP) accounts. The cost of operations consists of labor, tools, machine costs, vendor costs, and overhead. When an operation in the production process is performed, costs are generated. These costs are referred to as consumption. Consumption can be posted automatically or manually by entering a route card or job card journal. Hours or quantity can be used to calculate the route consumption. See an example of each in the following sections:

## Examples

## Example 1: Route consumption based on hourly cost

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Operation</p></td>
<td><p>Painting</p></td>
</tr>
<tr class="even">
<td><p>Work center</p></td>
<td><p>Paint sprayer with 1 person running the sprayer</p></td>
</tr>
<tr class="odd">
<td><p>Costs</p></td>
<td><ul>
<li><p>10 dollars per hour for 1 person</p></li>
<li><p>0.32 cents per hour for the cost of sprayer purchased for 2000 dollars with an estimated life of 3 years. Usage of sprayer estimated to be 40 hours per week</p></li>
<li><p>0.80 cents overhead calculated based on rent, utilities, etc.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Estimated cost per hour</p></td>
<td><p>11 dollars and 12 cents.</p></td>
</tr>
</tbody>
</table>


## Example 2: Route consumption based on quantity produced

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Operation</p></td>
<td><p>Assembly</p></td>
</tr>
<tr class="even">
<td><p>Work center</p></td>
<td><p>Assembly workers</p></td>
</tr>
<tr class="odd">
<td><p>Costs</p></td>
<td><p>2 dollars per item assembled per worker (piecework)</p></td>
</tr>
<tr class="even">
<td><p>Estimated cost per unit</p></td>
<td><p>2 dollars</p></td>
</tr>
</tbody>
</table>


## Work center

Work centers are the machine, persons, tools, or vendors used to perform the operation. They are used to determine capacity when scheduling. Examples of work centers are press machine, assembly workers, paint sprayer.

## Work in process (WIP)

If costs are posted during the production cycle, they are posted to WIP accounts in the General ledger. When the production process is completed, the finished goods inventory account is posted with the total cost of the production and the WIP accounts offset. If you are not using WIP, costs are not posted until the production is completed. This also means that the raw materials' quantity-on-hand is not reduced until the production is complete.

  


