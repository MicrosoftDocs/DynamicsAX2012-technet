---
title: About multisite activation readiness
TOCTitle: About multisite activation readiness
ms:assetid: ad01439b-d81f-439f-9c8c-2e0acae556e5
ms:mtpsurl: https://technet.microsoft.com/library/Gg188987(v=AX.60)
ms:contentKeyID: 35410567
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# About multisite activation readiness 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The upgrade readiness check performs a series of configuration analysis tests to identify issues that could potentially affect data upgrade. These checks include verification that the multisite configuration is setup correctly. This includes verifying that the site and warehouse hierarchies are specified.


> [!IMPORTANT]
> <P>The upgrade readiness tests will not complete until the site structure is configured.</P>



The following tables list and describe the conditions and requirements for multisite activation that the readiness check tests for. These tests ensure that the activation process is completed without errors.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p><strong>Conditions</strong></p></td>
<td><p><strong>Requirement</strong></p></td>
</tr>
<tr class="even">
<td><p>Site and warehouse relations</p></td>
<td><p>None</p></td>
<td><p>A site is assigned to all warehouses.</p></td>
</tr>
<tr class="odd">
<td><p>Site and warehouse relations</p></td>
<td><p>None</p></td>
<td><p>Warehouses only refer to quarantine warehouses that are located on the same site.</p></td>
</tr>
<tr class="even">
<td><p>Site and work center relations</p></td>
<td><p>None</p></td>
<td><p>All work centers are linked to a site.</p></td>
</tr>
<tr class="odd">
<td><p>Site and production unit relations</p></td>
<td><p>None</p></td>
<td><p>All production units are linked to a site.</p></td>
</tr>
<tr class="even">
<td><p>Site and production unit relations</p></td>
<td><p>None</p></td>
<td><p>Production units only refer to picking warehouses or storage warehouses that are located at the same site.</p></td>
</tr>
<tr class="odd">
<td><p>Site and production unit relations</p></td>
<td><p>None</p></td>
<td><p>All work centers that are associated with a production unit are linked to the same site as the production unit.</p></td>
</tr>
<tr class="even">
<td><p>Physical inventory dimension group setup</p></td>
<td><ul>
<li><p>More than one site is defined.</p></li>
<li><p>An inventory dimension group exists where the warehouse dimension is not set to <strong>Physical inventory</strong>.</p></li>
</ul></td>
<td><p>For each item that uses this dimension group, all transactions are related to the same site. Otherwise, some sites may have with negative inventory values.</p></td>
</tr>
<tr class="odd">
<td><p>Financial inventory dimension group setup</p></td>
<td><ul>
<li><p>More than one site is defined.</p></li>
<li><p>An inventory dimension group exists where the warehouse dimension is not set to <strong>Financial inventory</strong>.</p></li>
</ul></td>
<td><p>For each item that uses this dimension group, all transactions are related to the same site. Otherwise, the cost may change.</p></td>
</tr>
<tr class="even">
<td><p>Financial inventory dimension group setup</p></td>
<td><p>None</p></td>
<td><p>Activation will not result in cross-site markings.</p></td>
</tr>
<tr class="odd">
<td><p>Deleted warehouses</p></td>
<td><p>None</p></td>
<td><p>Closed inventory transactions do not refer to a warehouse that has been deleted. <strong>InventDim</strong> records cannot refer to a deleted warehouse.</p>
<div class="alert">

> [!NOTE]
> <P>If this check fails, the validation displays a list of any deleted warehouses.</P>
> <P>You will have to re-create these warehouses, assign them to a site, and then re-run the upgrade readiness check.</P>
> <P>After the upgrade is complete, you can delete the warehouses again, because no transactions are created for these warehouses during the activation process.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Inventory dimensions in virtual companies</p></td>
<td><p>One or more virtual companies exist.</p></td>
<td><p>Tables that contain <strong>InventDimId</strong> fields are not shared across companies.</p></td>
</tr>
<tr class="odd">
<td><p>Intercompany configuration</p></td>
<td><p>Intercompany endpoints are defined.</p></td>
<td><p>For all intercompany action policies, the value mapping of the handling warehouse that is defined in the document configuration is set to not specified.</p></td>
</tr>
<tr class="even">
<td><p>Site and task group relations</p></td>
<td><p>None</p></td>
<td><p>All work centers in a task group belong to the same site. This site must be the same site that is defined on the task group.</p></td>
</tr>
<tr class="odd">
<td><p>Site and task group relations</p></td>
<td><p>None</p></td>
<td><p>All task groups are assigned only to work centers located on the same site.</p></td>
</tr>
<tr class="even">
<td><p>Site and bill of materials relations</p></td>
<td><p>None</p></td>
<td><p>All warehouses that are defined in the bill of materials are associated with the same site. Master planning assumes 0 (zero) days for picking.</p></td>
</tr>
<tr class="odd">
<td><p>Site and bill of materials relations</p></td>
<td><p>None</p></td>
<td><p>If a site is defined in the BOM version, all warehouses that are defined in the BOM belong to that same site.</p></td>
</tr>
<tr class="even">
<td><p>Site and route relations</p></td>
<td><p>None</p></td>
<td><p>All work centers that are defined in a route belong to the same site.</p></td>
</tr>
<tr class="odd">
<td><p>Site and route relations</p></td>
<td><p>None</p></td>
<td><p>A task group that is assigned to a route contains only work centers that are assigned to the same site as the work centers that are defined in the route.</p></td>
</tr>
<tr class="even">
<td><p>Site and route relations</p></td>
<td><p>None</p></td>
<td><p>All work centers that are defined in a route version belong to the same site.</p></td>
</tr>
<tr class="odd">
<td><p>Site and route relations</p></td>
<td><p>None</p></td>
<td><p>For each route version that is assigned to a site, all work centers that are defined in the route belong to the same site.</p></td>
</tr>
<tr class="even">
<td><p>Shipment setup</p></td>
<td><p>A warehouse is not defined on the shipment</p></td>
<td><p>Multisite cannot be activated. You must either complete or cancel the shipment before you upgrade.</p></td>
</tr>
<tr class="odd">
<td><p>Shipment template setup</p></td>
<td><p>A warehouse is not defined on the shipment template</p></td>
<td><p>Multisite cannot be activated. You must add a warehouse to the shipment template before you upgrade.</p></td>
</tr>
<tr class="even">
<td><p>Fallback warehouse</p></td>
<td><p>None</p></td>
<td><p>A fallback warehouse is selected on the <strong>Other</strong> tab in the <strong>Company information</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p>Inventory dimensions</p></td>
<td><p>None</p></td>
<td><p>Inventory dimension combinations do not include both the site dimension and the warehouse dimension.</p>
<div class="alert">

> [!NOTE]
> <P>This check will fail when there is a defect in the application. To recover, you must manually clean up the <STRONG>Inventory Dimension</STRONG> table.</P>


</div></td>
</tr>
</tbody>
</table>


## Additional readiness checks

The following table describes additional readiness checks that the validation performs.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p><strong>Conditions</strong></p></td>
<td><p><strong>Requirement</strong></p></td>
</tr>
<tr class="even">
<td><p>Site and production order relations</p></td>
<td><p>None</p></td>
<td><p>Open production orders do not span multiple sites.</p>
<div class="alert">

> [!NOTE]
> <P>If this check fails, the validation displays a list of the production orders that span multiple sites.</P>
> <P>You must end these production orders before upgrading.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Empty intercompany inventory dimensions</p></td>
<td><p>None</p></td>
<td><p>The intercompany inventory dimensions table is empty. This table is used only for temporary storage of data.</p></td>
</tr>
<tr class="even">
<td><p>Empty intercompany inventory summary</p></td>
<td><p>None</p></td>
<td><p>The intercompany on-hand inventory table is empty. This table is used only to store data temporarily.</p></td>
</tr>
<tr class="odd">
<td><p>Empty quarantine orders</p></td>
<td><p>None</p></td>
<td><p>All quarantine orders are associated with a warehouse.</p></td>
</tr>
<tr class="even">
<td><p>Empty inventory summary delta</p></td>
<td><p>None</p></td>
<td><p>The on-hand inventory changes table is empty. This table is used only to store data temporarily.</p></td>
</tr>
<tr class="odd">
<td><p>Empty inventory summary delta dimension</p></td>
<td><p>None</p></td>
<td><p>The on-hand inventory checks table is empty. This table is used only to store data temporarily.</p></td>
</tr>
<tr class="even">
<td><p>Inventory transaction ID on the same site</p></td>
<td><p>None</p></td>
<td><p>All open inventory transactions with the same inventory transaction ID, or Lot ID, are associated with the same site.</p>
<div class="alert">

> [!NOTE]
> <P>If this check fails, the validation displays a list of the lot IDs for which inventory transactions will be split across multiple sites.</P>
> <P>You must close these inventory transactions by financially updating the parent transaction before proceeding with the upgrade.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Empty transfer journal lines</p></td>
<td><p>None</p></td>
<td><p>A warehouse is assigned to all transfer journal lines.</p></td>
</tr>
<tr class="even">
<td><p>Empty inventory transfer lines</p></td>
<td><p>None</p></td>
<td><p>A warehouse is assigned to all inventory transfer lines.</p></td>
</tr>
<tr class="odd">
<td><p>Empty warehouse management orders</p></td>
<td><p>None</p></td>
<td><p>A warehouse is assigned to all warehouse management orders.</p></td>
</tr>
<tr class="even">
<td><p>Empty warehouse management order transactions</p></td>
<td><p>None</p></td>
<td><p>A warehouse is assigned to all warehouse management order transactions</p></td>
</tr>
</tbody>
</table>


## See also

[Configure site structure (form)](https://technet.microsoft.com/library/hh202081\(v=ax.60\))

  


