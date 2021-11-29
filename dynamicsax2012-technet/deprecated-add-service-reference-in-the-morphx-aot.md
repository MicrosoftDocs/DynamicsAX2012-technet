---
title: 'Deprecated: Add Service Reference in the MorphX AOT'
TOCTitle: Add Service Reference in the MorphX AOT
ms:assetid: 00da95fb-1704-4222-81ec-5c0a83f600d9
ms:mtpsurl: https://technet.microsoft.com/library/Dn507110(v=AX.60)
ms:contentKeyID: 59623200
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Add Service Reference in the MorphX AOT 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009 and earlier versions, the Add Service Reference feature enabled the consumption of external service references from X++ code.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reason for deprecation</p></td>
<td><p>The MorphX feature, which consumed external services, had severe limitations. Because of a strategic shift toward making .NET development more mainstream for Microsoft Dynamics AX 2012, the consumption of external services is now done in Microsoft Visual Studio .NET, by using the Add Service Reference feature that is available in Visual Studio. AX 2012 dramatically improves interoperability from .NET to X++.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. Use the Add Service Reference feature in Visual Studio .NET to consume the external service via a service proxy in Visual Studio .NET. The resulting managed project can be added to the Microsoft Dynamics AX Application Object Tree (AOT) by using the Microsoft Dynamics AX Application Explorer. The project then becomes available for consumption in X++.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>Any existing service references that are used in X++ code might have to be refreshed and recompiled for consumption by using the managed project artifacts.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>X++ code that references service proxies that were added by using Add Service Reference in AX 2009 MorphX must be revised and recompiled.</p></td>
</tr>
</tbody>
</table>


## See also

[How to: Add a Reference to a .NET Assembly](https://technet.microsoft.com/library/gg881320\(v=ax.60\))

  


