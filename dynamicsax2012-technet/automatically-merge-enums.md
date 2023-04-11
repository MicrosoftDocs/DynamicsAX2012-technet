---
title: Automatically merge enums
TOCTitle: Automatically merge enums
ms:assetid: b2d20f9b-a81d-46f9-9649-14ff6de2c472
ms:mtpsurl: https://technet.microsoft.com/library/JJ677309(v=AX.60)
ms:contentKeyID: 49384080
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Automatically merge enums 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Each code upgrade checklist in Microsoft Dynamics AX 2012 R2 or R3 contains the optional **Automatically merge enums** task, which is run before the application is compiled. This task identifies enums (enumerated data types) that differ between versions, but that can be merged automatically. By merging enums before compiling, you can reduce the number of compile errors and the time that is required to resolve code conflicts.

## How enum versions are merged

In the **Automatically merge enums** task, the upgrade framework checks for cases that meet the following conditions:

  - The customer has modified the enum in a higher layer, and that layer has fewer members than the lower SYS layer.

  - Microsoft modifies the enum in the SYS layer for Microsoft Dynamics AX 2012 R2 or R3.

  - The modifications do not conflict, that is, no two members share the same name or the same integer Enum Value property.

If these conditions are met, the upgrade framework merges the two objects. For example, an enum FOO has the following history:

1.  SYS ENUM FOO = A //Microsoft shipped enum FOO with value A in Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack.

2.  USR ENUM FOO = B //The customer added a value B to enum FOO in Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack.

3.  SYS ENUM FOO = A, C //Microsoft adds a value C to the enum in Microsoft Dynamics AX 2012 R2.

The following table illustrates this scenario.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Layer</p></th>
<th><p>Baseline value</p></th>
<th><p>Microsoft Dynamics AX 2012 R2 or R3 value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>USR</p></td>
<td><p>A, B</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>SYS</p></td>
<td><p>A</p></td>
<td><p>A, C</p></td>
</tr>
</tbody>
</table>


The customized and default enums can be merged as follows. The merger copies the new Microsoft member C from SYS into the USR layer, since otherwise it would be masked by the higher layer.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Layer</p></th>
<th><p>Baseline value</p></th>
<th><p>Microsoft Dynamics AX 2012 R2 or R3 value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>USR</p></td>
<td><p>A, B</p></td>
<td><p>A, B, C</p></td>
</tr>
<tr class="even">
<td><p>SYS</p></td>
<td><p>A</p></td>
<td><p>A, C</p></td>
</tr>
</tbody>
</table>


## Merging the enums

When you click **Automatically merge enums**, a progress indicator shows that merges are occurring. When the merge process is completed, an Infolog window opens. This window lists each enum that was successfully merged and conflicting enums that could not be merged. The unmerged enums require manual conflict resolution.


> [!IMPORTANT]
> <P>Any change to an integer Enum Value property that is used in business data will require the creation of a data upgrade script to resolve the difference.</P>


  


