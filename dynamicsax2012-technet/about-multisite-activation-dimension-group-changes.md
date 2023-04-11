---
title: About multisite activation - dimension group changes
TOCTitle: About multisite activation - dimension group changes
ms:assetid: b8f5cda9-4219-4a29-be71-758a3c949333
ms:mtpsurl: https://technet.microsoft.com/library/Dd309977(v=AX.60)
ms:contentKeyID: 45442192
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- dimension groups
- multisite activation
- site dimension
- warehouse dimension
audience: Application User
ms.search.region: Global
---

# About multisite activation - dimension group changes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When the multisite functionality is activated, the settings for all dimension groups are updated to ensure that all inventory-related transactions can be associated with a site.


> [!NOTE]
> <P>Multisite is activated during the upgrade process from Microsoft Dynamics AX 4.0 to Microsoft Dynamics AX 2012, or before the upgrade process from Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012. Multisite cannot be activated as a separate activity.</P>



The following table summarizes the changes that are made to the settings of the dimension groups during the activation.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Dimension group setting</strong></p></td>
<td><p><strong>Site dimension</strong></p></td>
<td><p><strong>Warehouse dimension</strong></p></td>
</tr>
<tr class="even">
<td><p>Active</p></td>
<td><p>This dimension is selected during the activation. You cannot modify the setting.</p></td>
<td><p>This dimension is selected during the activation. You cannot modify the setting.</p></td>
</tr>
<tr class="odd">
<td><p>Setup / Mandatory</p></td>
<td><p>This dimension is selected during the activation. You cannot modify the setting.</p></td>
<td><p>There is no change to this dimension.</p></td>
</tr>
<tr class="even">
<td><p>Setup / Primary stocking</p></td>
<td><p>This dimension is selected during the activation. You cannot modify the setting.</p></td>
<td><p>There is no change to this dimension.</p></td>
</tr>
<tr class="odd">
<td><p>Setup / Serial number control</p></td>
<td><p>This setting is cleared during the activation. You cannot modify the setting.</p></td>
<td><p>This setting is cleared during the activation. You cannot modify the setting.</p></td>
</tr>
<tr class="even">
<td><p>Setup / Blank receipt allowed</p></td>
<td><p>This setting is cleared during the activation. You cannot modify the setting.</p></td>
<td><p>This setting is cleared during the activation. You cannot modify the setting.</p></td>
</tr>
<tr class="odd">
<td><p>Setup / Blank issue allowed</p></td>
<td><p>This setting is cleared during the activation. You cannot modify the setting.</p></td>
<td><p>This setting is cleared during the activation. You cannot modify the setting.</p></td>
</tr>
<tr class="even">
<td><p>Where-used / Physical inventory</p></td>
<td><p>This dimension is selected during the activation. You cannot modify the setting.</p></td>
<td><p>There is no change to this dimension.</p></td>
</tr>
<tr class="odd">
<td><p>Where-used / Financial inventory</p></td>
<td><p>This dimension is selected during the activation. You cannot modify the setting.</p></td>
<td><p>There is no change to this dimension.</p></td>
</tr>
<tr class="even">
<td><p>Coverage / Coverage plan by dimension</p></td>
<td><p>If this dimension is selected for the warehouse, it is selected during the activation.</p></td>
<td><p>There is no change to this dimension.</p></td>
</tr>
<tr class="odd">
<td><p>Use in price search / For purchase prices</p></td>
<td><p>If this dimension is selected for the warehouse, it is selected during the activation.</p></td>
<td><p>There is no change to this dimension.</p></td>
</tr>
<tr class="even">
<td><p>Use in price search / For sales prices</p></td>
<td><p>If this dimension is selected for the warehouse, it is selected during the activation.</p></td>
<td><p>There is no change to this dimension.</p></td>
</tr>
</tbody>
</table>


## See also

[About sites and the multisite functionality](about-sites-and-the-multisite-functionality.md)

[Multisite activation - dimension inconsistency clean up (class form)](https://technet.microsoft.com/library/dd309967\(v=ax.60\))

  


