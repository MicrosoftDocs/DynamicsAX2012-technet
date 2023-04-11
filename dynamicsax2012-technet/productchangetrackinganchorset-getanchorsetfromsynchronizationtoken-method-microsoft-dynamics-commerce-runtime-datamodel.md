---
title: ProductChangeTrackingAnchorSet.GetAnchorSetFromSynchronizationToken Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetAnchorSetFromSynchronizationToken Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.GetAnchorSetFromSynchronizationToken(System.Char[],System.Int64@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.getanchorsetfromsynchronizationtoken(v=AX.60)
ms:contentKeyID: 62208600
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.GetAnchorSetFromSynchronizationToken
dev_langs:
- CSharp
- C++
- VB
---

# GetAnchorSetFromSynchronizationToken Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns an object representing the sync anchor set from a given synchronization token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAnchorSetFromSynchronizationToken ( _
    token As Char(), _
    <OutAttribute> ByRef marker As Long _
) As ProductChangeTrackingAnchorSet
'Usage
Dim token As Char()
Dim marker As Long
Dim returnValue As ProductChangeTrackingAnchorSet

returnValue = ProductChangeTrackingAnchorSet.GetAnchorSetFromSynchronizationToken(token, _
    marker)
```

``` csharp
public static ProductChangeTrackingAnchorSet GetAnchorSetFromSynchronizationToken(
    char[] token,
    out long marker
)
```

``` c++
public:
static ProductChangeTrackingAnchorSet^ GetAnchorSetFromSynchronizationToken(
    array<wchar_t>^ token, 
    [OutAttribute] long long% marker
)
```

#### Parameters

  - token  
    Type: [System.Char](https://technet.microsoft.com/library/k493b04s\(v=ax.60\))\[\]  

<!-- end list -->

  - marker  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
An object representing the anchor set encoded in the token.  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

