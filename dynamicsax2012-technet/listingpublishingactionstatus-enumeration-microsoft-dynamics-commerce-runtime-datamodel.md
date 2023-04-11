---
title: ListingPublishingActionStatus Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ListingPublishingActionStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.listingpublishingactionstatus(v=AX.60)
ms:contentKeyID: 49825772
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus.Done
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus.Failed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus.InProgress
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus.Ready
dev_langs:
- CSharp
- C++
- VB
---

# ListingPublishingActionStatus Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the publishing status of a given listing.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration ListingPublishingActionStatus
'Usage
Dim instance As ListingPublishingActionStatus
```

``` csharp
public enum ListingPublishingActionStatus
```

``` c++
public enum class ListingPublishingActionStatus
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>No publishing action status.</td>
</tr>
<tr class="even">
<td></td>
<td>Ready</td>
<td>A status indicating that publishing is ready to begin.</td>
</tr>
<tr class="odd">
<td></td>
<td>InProgress</td>
<td>A status indicating that publishing is currently in progress.</td>
</tr>
<tr class="even">
<td></td>
<td>Done</td>
<td>A status indicating that publishing has completed successfully.</td>
</tr>
<tr class="odd">
<td></td>
<td>Failed</td>
<td>A status indicating that publishing has failed..</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

