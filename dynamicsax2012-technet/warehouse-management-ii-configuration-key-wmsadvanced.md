---
title: Warehouse Management II configuration key (WMSAdvanced)
TOCTitle: Warehouse Management II configuration key (WMSAdvanced)
ms:assetid: 009d2652-4f4d-4365-b057-aa2927fed6e7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548483(v=AX.60)
ms:contentKeyID: 36941189
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Data_Dictionary.Configuration_Keys.WMSAdvanced
---

# Warehouse Management II configuration key (WMSAdvanced) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>Microsoft Dynamics AX 2012 R3 includes new Warehouse and Transportation management modules that are enabled by a single configuration key, along with the previously released Warehouse management II module. Users should enable the configuration key for <STRONG>ONLY ONE</STRONG> of these modules, but not both, in a single-instance, single-partition deployment. Although technically feasible, enabling the configuration keys for both of these modules in a single-instance, single-partition deployment is not supported by Microsoft.&nbsp;</P>



The **Warehouse management II** configuration key controls access to advanced warehouse management forms and functions, such as shipment templates and picking routes.

You cannot enable or disable this key in the **License configuration** form.

## Forms enabled by the configuration key

The following forms are available when the configuration key is enabled.

## Inventory management forms

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Blocking causes</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa577108(v=ax.60)">Blocking cause (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Deliver picked items</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh803015(v=ax.60)">Deliver picked items (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Forklift</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa590371(v=ax.60)">Forklift (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Output orders</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa635055(v=ax.60)">Output orders (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/hh352340(v=ax.60)">(PM) Output order (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Transactions</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa587481(v=ax.60)">Inventory order (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Outbound rules</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Picking routes</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa582503(v=ax.60)">Picking routes (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/hh328618(v=ax.60)">(PM) Picking routes (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Picking lines</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa617832(v=ax.60)">Picking line (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Approve line</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa551825(v=ax.60)">Approve line (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Shipment reservation combinations</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209514(v=ax.60)">Shipment reservation combinations (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Shipment reservation sequences</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh227537(v=ax.60)">Shipment reservation sequences (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Show lines</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa557910(v=ax.60)">Shipment lines (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/hh328622(v=ax.60)">(PM) Shipment lines (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Shipment staging</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh242497(v=ax.60)">Shipment staging (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/hh328635(v=ax.60)">(PM) Shipment staging (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Shipment templates</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa634909(v=ax.60)">Shipment templates (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Create shipment</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Update store areas</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa550377(v=ax.60)">Store areas (form)</a></p>
<div class="alert">

> [!TIP]
> <P>You can access the <STRONG>Update store areas</STRONG> wizard from this location:</P>
> <UL>
> <LI>
> <P>Click <STRONG>Inventory management</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Inventory breakdown</STRONG> &gt; <STRONG>Warehouses</STRONG>. Click <STRONG>Functions</STRONG>, and then click <STRONG>Update store areas</STRONG>.</P></LI></UL>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Store zones</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa596993(v=ax.60)">Store zones (form)</a></p></td>
</tr>
</tbody>
</table>


## Additional information about this configuration key

The following table provides information about how this configuration key relates to other configuration keys and license codes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>License code</p></td>
<td><p><strong>Warehouse management II</strong></p></td>
</tr>
<tr class="even">
<td><p>Parent key</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Child keys</p></td>
<td><p><a href="pallets-configuration-key-wmspallet.md">Pallets configuration key (WMSPallet)</a></p>
<div class="alert">

> [!NOTE]
> <P>The configuration keys listed here may have additional child configuration keys. Click the link for more information about a configuration key.</P>


</div></td>
</tr>
</tbody>
</table>


For more information about how license codes and configuration keys work together, see [About license codes and configuration keys](https://technet.microsoft.com/en-us/library/aa548653\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

