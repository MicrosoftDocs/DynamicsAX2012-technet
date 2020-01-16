---
title: 'Deprecated: Country/region configuration keys'
TOCTitle: Country/region configuration keys
ms:assetid: 638100e3-2520-4a50-ae55-1ca74f496c33
ms:mtpsurl: https://technet.microsoft.com/library/Dn527128(v=AX.60)
ms:contentKeyID: 59623257
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Country/region configuration keys 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2009 and earlier versions, country/region configuration keys are used to enable and display country/region-specific features.

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
<td><p>The country/region configuration keys are installation-specific. The requirement was for control over the features that are available to individual companies in multinational scenarios. The capability to make features available based on the company’s location, the customer’s location, and so on was also required. Country/region context was introduced to meet this requirement, and this feature replaces country/region configuration keys for control over feature availability.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature remains only for backward compatibility. Although the feature will not be removed until the next version of Microsoft Dynamics AX, a replacement feature is already available. To control feature availability based on the location of the legal entity, Microsoft Dynamics AX 2012 uses the country/region that is associated with the legal entity’s primary address. For example, if the address of the legal entity is in Canada, users can see and work with Canada-specific features.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>This change does not affect application upgrade.</p>
<p>For information about how to use country/region configuration keys when you upgrade an existing version of Microsoft Dynamics AX to AX 2012, see the <a href="https://go.microsoft.com/fwlink/?linkid=163798">Microsoft Dynamics AX 2012 Upgrade Guide</a>.</p></td>
</tr>
</tbody>
</table>

  


