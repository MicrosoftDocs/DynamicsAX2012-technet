---
title: "What's new: Country/Region Context"
TOCTitle: Country/Region Context
ms:assetid: bcee3a7e-d50a-4d34-8460-2f2d69665367
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527232(v=AX.60)
ms:contentKeyID: 59623360
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Country/Region Context [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009 and earlier versions, country/region configuration keys were used to enable and display country/region-specific features. To control feature availability based on the location of the legal entity, Microsoft Dynamics AX 2012 uses the country/region that is associated with the legal entity’s primary address. For example, if the address of the legal entity is in Canada, users can see and work with Canada-specific features.

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
<td><p>Required</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Country/region-specific features are now enabled for each legal entity instead of each instance of Microsoft Dynamics AX. Therefore, for example, a single instance can have one legal entity that is located in Germany, for which German-specific functionality is enabled, and another legal entity that is located in Canada, for which Canada-specific functionality is enabled. In this case, the set of functionalities that is enabled for one legal entity does not affect the other legal entities.

Country/region context simplifies setup, because parameters are no longer required if you want to enable country/region-specific features. These features are implicitly enabled or disabled based on the address of the legal entity.

## Comparison with AX 2009

The way that country/region-specific features are enabled and displayed has changed.

## Display of country/region-specific features

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View country/region-specific features.</p></td>
<td><p>Configuration keys were used to enable and display country/region-specific features.</p></td>
<td><p>Country/region-specific features are enabled based on the location of the primary address for the legal entity.</p></td>
<td><p>The process for enabling and displaying country/region-specific feature is simplified.</p></td>
</tr>
</tbody>
</table>


## More information

For more information about the deprecation of the country/region configuration keys, see [Deprecated: Country/region configuration keys](deprecated-country-region-configuration-keys.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

