---
title: Replenish inventory overview (Retail essentials)
TOCTitle: Replenish inventory overview (Retail essentials)
ms:assetid: 88904b0c-4c0e-4631-ada3-28afc854cf97
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736913(v=AX.60)
ms:contentKeyID: 62200387
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Replenish inventory overview (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The topics in this section provide information about how to replenish inventory.

[Set up product packages (Retail essentials)](set-up-product-packages-retail-essentials.md)

[Set up replenishment hierarchies (Retail essentials)](set-up-replenishment-hierarchies-retail-essentials.md)

[Set up replenishment rules (Retail essentials)](set-up-replenishment-rules-retail-essentials.md)

[Set up replenishment service categories (Retail essentials)](set-up-replenishment-service-categories-retail-essentials.md)

## Methods for replenishing inventory

Typically, replenishment is performed at the head office. You can replenish the inventory at stores by using two methods:

  - **Cross-docking** – Create transfer orders that are based on purchase orders.
    
    The term cross-docking originated in distribution warehouses. At these warehouses, trucks arrive on one side of the loading dock, the shipments are unloaded and reorganized by destination, and then the shipments are loaded onto outgoing trucks on the other side of the loading dock.

  - **Buyer's push** – Create original transfer orders.


> [!NOTE]
> <P>Regardless of which replenishment method you use, if the stores that inventory is being distributed to are in another legal entity, sales orders and purchase orders are automatically created.</P>



For both replenishment methods, you can specify one of three distribution methods:

  - Distribution based on location weight

  - Distribution based on replenishment rules

  - Distribution of a fixed quantity to all stores

Before you use either cross-docking or buyer's push to replenish inventory, you should set up the following elements:

  - Organization hierarchy

  - Replenishment rules

  - Service categories

## Forms for the Replenishing inventory business process component

The following table lists the forms that support the Replenishing inventory business process component. The table entries are organized first by task, and then alphabetically by the name of the form that is used.


> [!NOTE]
> <P>Before you can open some of the forms in the following table, you must enter information or parameter settings in the program.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Business process component task</p></th>
<th><p>Form name</p></th>
<th><p>Usage</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up replenishment.</p></td>
<td><p><strong>Organization hierarchies</strong></p></td>
<td><p>Create a hierarchy for a retail organization.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Organization hierarchy purposes</strong></p></td>
<td><p>Assign a purpose to the retail organization hierarchy.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Replenishment rules</strong></p></td>
<td><p>Set up replenishment rules.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Service category</strong></p></td>
<td><p>Set up service categories.</p></td>
</tr>
<tr class="odd">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Cross-dock.</p></td>
<td><p><strong>Planned cross docking</strong></p></td>
<td><p>Use cross-docking to create transfer orders for existing purchase orders.</p></td>
</tr>
<tr class="odd">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Allocate inventory.</p></td>
<td><p><strong>Buyer's push</strong></p></td>
<td><p>Create transfer orders to distribute inventory among stores and warehouses.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

