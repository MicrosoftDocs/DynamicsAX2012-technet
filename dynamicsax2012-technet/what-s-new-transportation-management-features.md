---
title: "What's new: Transportation management features"
TOCTitle: Transportation management features
ms:assetid: 3bdb9bed-b192-4d6d-9eaa-717f6075ce6e
ms:mtpsurl: https://technet.microsoft.com/library/Dn716027(v=AX.60)
ms:contentKeyID: 62200283
author: tonyafehr
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new: Transportation management features 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A new module, **Transportation management**, has been added in Microsoft Dynamics AX 2012. This topic is a high-level overview of the feature areas that are included in this module and it also lists the new Transportation management features that were added in Microsoft Dynamics AX 2012 R3 Cumulative Update 8.


> [!NOTE]
> <P>Microsoft Dynamics AX 2012 R3 includes new Warehouse and Transportation management modules that are enabled by a single configuration key, along with the previously released Warehouse management II module. Users should enable the configuration key for <STRONG>ONLY ONE</STRONG> of these modules, but not both, in a single-instance, single-partition deployment. Although technically feasible, enabling the configuration keys for both of these modules in a single-instance, single-partition deployment is not supported by Microsoft.&nbsp;</P>



## Rating

Configure rating structures and shop for rates based on charges, such as fuel and customs duties. For example, the rate of an assignment can reflect the price of fuel in the state or the country/region where the transport is carried out. For more information, see the following topics:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="rating-setup.md">Rating setup</a></p></td>
</tr>
<tr class="even">
<td><p><a href="set-up-accessorial-assignments.md">Set up accessorial assignments</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="set-up-carrier-fuel-indexes.md">Set up carrier fuel indexes</a></p></td>
</tr>
</tbody>
</table>


## Routing

Set up route plans and route guides for complex transportation processes and determine carriers’ routes based on mode. Based on the routing information, you can select the route that fits your needs. For example, if you prioritize price over time, you might want to plan a route that uses a train for transportation instead of an airplane. For more information, see the following topics:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="set-up-a-transportation-mode-and-method-for-a-shipping-carrier.md">Set up a transportation mode and method for a shipping carrier</a></p></td>
</tr>
<tr class="even">
<td><p><a href="set-up-a-route-plan-and-routing-guide-for-freight-transportation.md">Set up a route plan and routing guide for freight transportation</a></p></td>
</tr>
</tbody>
</table>


## Transportation engines

Use transportation engines to define the logic that is used for rating and routing in Transportation management. A transportation engine can be used to calculate specific task information, such as a carrier’s transportation rate. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="set-up-transportation-management-engines.md">Set up transportation management engines</a></p></td>
</tr>
</tbody>
</table>


## Freight reconciliation

Use an automatic or a manual process to reconcile freight bills with invoices. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="freight-reconciliation.md">Freight reconciliation</a></p></td>
</tr>
</tbody>
</table>


## Appointment scheduling

Set up appointment types and set up appointment notifications as batch jobs to track upcoming appointments. For example, you can create an appointment schedule for a warehouse to send periodic notifications for scheduled appointments. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="set-up-appointment-scheduling-parameters.md">Set up appointment scheduling parameters</a></p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8

Microsoft Dynamics AX 2012 R3 Cumulative Update 8 introduces a load building feature that lets you automatically build loads using a load building workbench. You set up filters that define a subset of supply or demand lines, load building templates, and a strategy for load building. At the touch of a button, suggested loads are generated, which can later be turned into actual loads. This feature is designed for extensibility so that advanced load building strategies can easily be plugged in. For more information, see [Automate the process of building loads](automate-the-process-of-building-loads.md).

## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 9

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Improvements to the Bill of Lading</p></td>
<td><p>The Bill of Lading now includes additional fields and it’s possible to edit the Bill of Lading before printing it.</p></td>
</tr>
<tr class="even">
<td><p>Printing multiple packing slips in the Load planning workbench</p></td>
<td><p>It is now possible to print multiple packing slips directly from the load planning workbench by selecting multiple loads.</p></td>
</tr>
<tr class="odd">
<td><p>Enabling freight reconciliation</p></td>
<td><p>There’s a new <strong>Freight reconciliation</strong> option on the <strong>Transportation management parameters</strong> form. If freight reconciliation is not used you can de-select this option and no freight bill records will be created.</p></td>
</tr>
</tbody>
</table>

  


