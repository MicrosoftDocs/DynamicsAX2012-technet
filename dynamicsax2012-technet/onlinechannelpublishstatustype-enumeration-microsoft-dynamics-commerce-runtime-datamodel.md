---
title: OnlineChannelPublishStatusType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OnlineChannelPublishStatusType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.onlinechannelpublishstatustype(v=AX.60)
ms:contentKeyID: 49823522
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType.Draft
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType.Failed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType.InProgress
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType.Published
dev_langs:
- CSharp
- C++
- VB
---

# OnlineChannelPublishStatusType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the publishing status of an online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration OnlineChannelPublishStatusType
'Usage
Dim instance As OnlineChannelPublishStatusType
```

``` csharp
[DataContractAttribute]
public enum OnlineChannelPublishStatusType
```

``` c++
[DataContractAttribute]
public enum class OnlineChannelPublishStatusType
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
<td>No publishing status.</td>
</tr>
<tr class="even">
<td></td>
<td>Draft</td>
<td>Channel is in draft state.</td>
</tr>
<tr class="odd">
<td></td>
<td>InProgress</td>
<td>Channel publishing is currently in progress.</td>
</tr>
<tr class="even">
<td></td>
<td>Published</td>
<td>Channel has been published successfully.</td>
</tr>
<tr class="odd">
<td></td>
<td>Failed</td>
<td>Channel was not published successfully.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

