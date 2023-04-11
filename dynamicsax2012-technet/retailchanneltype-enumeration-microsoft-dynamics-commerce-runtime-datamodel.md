---
title: RetailChannelType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailChannelType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retailchanneltype(v=AX.60)
ms:contentKeyID: 49837916
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType.OnlineMarketplace
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType.OnlineStore
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType.RetailStore
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType.SharePointOnlineStore
dev_langs:
- CSharp
- C++
- VB
---

# RetailChannelType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the channel type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration RetailChannelType
'Usage
Dim instance As RetailChannelType
```

``` csharp
public enum RetailChannelType
```

``` c++
public enum class RetailChannelType
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
<td>An unspecified type.</td>
</tr>
<tr class="even">
<td></td>
<td>RetailStore</td>
<td>A physical retail store.</td>
</tr>
<tr class="odd">
<td></td>
<td>OnlineStore</td>
<td>An online web storefront.</td>
</tr>
<tr class="even">
<td></td>
<td>OnlineMarketplace</td>
<td>An online marketplace where third parties list their products and/or services while transactions are processed by the marketplace operator.</td>
</tr>
<tr class="odd">
<td></td>
<td>SharePointOnlineStore</td>
<td>An online web storefront hosted on Microsoft SharePoint.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the RetailChannelType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

