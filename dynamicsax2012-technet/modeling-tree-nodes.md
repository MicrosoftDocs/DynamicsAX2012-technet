---
title: Modeling tree nodes
TOCTitle: Modeling tree nodes
ms:assetid: 778b947e-42ed-40b3-b87a-08e7a0eb3043
ms:mtpsurl: https://technet.microsoft.com/library/Aa550044(v=AX.60)
ms:contentKeyID: 36058210
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Modeling tree nodes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The modeling tree is a configuration program and is constructed from various nodes of different types.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



## Node types

The following table contains the principal node types that are available:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Code node</strong></p></td>
<td><p>Used to include X++ code in a product model.</p></td>
</tr>
<tr class="even">
<td><p><strong>IF node</strong></p></td>
<td><p>Used to inquire whether a certain condition is met. If it is, the operations described under the subnodes attached to the <strong>IF node</strong> will be performed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Switch node</strong></p></td>
<td><p>Used to inquire whether the value of a specific variable (the switch value) is equal to one of several possible outcomes.</p>
<p>The outcomes (the case values) tested for are defined as a set of case subnodes.</p>
<p>If the switch value is equal to the case value, the subnodes of the <strong>Case node</strong> are run.</p>
<p>You can also specify what should occur if no case value is equal to the switch value.</p></td>
</tr>
<tr class="even">
<td><p><strong>FOR node</strong></p></td>
<td><p>Used for repeating the same operation (the functionality defined in its subnodes) many times.</p></td>
</tr>
<tr class="odd">
<td><p><strong>BOM node</strong></p></td>
<td><p>Inserts a BOM line into the bill of materials that is being configured by the product model.</p></td>
</tr>
<tr class="even">
<td><p><strong>Route node</strong></p></td>
<td><p>Inserts a route operation into the route that is being configured by the product model.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Insert default route</strong></p></td>
<td><p>When a default route has been added to the product model, route nodes for the default route are inserted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Default node</strong></p></td>
<td><p>Can be used to insert either a default route, a bill of materials, or a route.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Table node</strong></p></td>
<td><p>Used to obtain values from one or more fields in a table.</p></td>
</tr>
<tr class="even">
<td><p><strong>Simple node</strong></p></td>
<td><p>Used for simple calculations.</p></td>
</tr>
<tr class="odd">
<td><p>Message (<strong>Information</strong>, <strong>Warning</strong>, <strong>Error</strong>)</p></td>
<td><p>Inserts an information message, a warning, or an error message.</p></td>
</tr>
</tbody>
</table>


## Subnodes

Several, but not all, of these principal node types can have subnodes attached to them.

  - Under the **BOM node** and **Route node**, you can attach a **Document handling** node that contains a document reference.

  - The **Switch node** and **IF node** are used to make decisions in the modeling tree. Both of these node types have special subnodes that can start new branches in the modeling tree. Each branch represents one of the choices that you can program the product model to make, based on values are that are selected for its modeling variables.

  - Under such branch nodes, and also under the **Case node**, you can attach nodes to each principal type, as listed in the **Node types** table.

  


