---
title: 'Deprecated: AIF endpoints'
TOCTitle: AIF endpoints
ms:assetid: f403ed0e-af81-47be-a2e6-97f18a06ac8b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527241(v=AX.60)
ms:contentKeyID: 59623369
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: AIF endpoints 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009 and earlier releases, the concept of Microsoft Dynamics AX Application Integration Framework (AIF) endpoints was used to group policies and processing options for integration messages in XML format that flow into and out of Microsoft Dynamics AX.

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
<td><p>Major conceptual changes in AIF have led to a simplified model for configuring and managing integrations in Microsoft Dynamics AX 2012. The number of top-level integration concepts has been reduced from about 17 to 2. Additionally, all proprietary Microsoft Dynamics AX integration concepts have been removed and replaced by industry-standard concepts.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. This feature has been rolled into the concept of integration ports. Ports not only subsume the concept of AIF endpoints but also have all the address-related settings that were previously set on AIF channels.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>The AIF configuration that occurs during installation is easier than the configuration in AX 2009. All proprietary Microsoft Dynamics AX concepts have been removed in favor of industry-standard concepts. Detailed documentation is planned for this area.</p>
<p>For more information, see <a href="what-s-new-services-and-application-integration-framework.md">What's new: Services and Application Integration Framework</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>All integration solution applications that were written to use AIF endpoints no longer function after upgrade. These applications must be recompiled after they are configured to point to the new AIF ports that replace endpoints. After upgrade, the administrator must also manually complete the configuration settings on the ports that are created by the upgrade.</p>
<p>For more information, see <a href="upgrade-aif-code.md">Upgrade AIF code</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[What's new: Services and Application Integration Framework](what-s-new-services-and-application-integration-framework.md)

  


