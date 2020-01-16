---
title: ProductChangeTrackingAnchorSet.GetSynchronizationTokenFromAnchorSet Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetSynchronizationTokenFromAnchorSet Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.GetSynchronizationTokenFromAnchorSet(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.getsynchronizationtokenfromanchorset(v=AX.60)
ms:contentKeyID: 62202995
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.GetSynchronizationTokenFromAnchorSet
dev_langs:
- CSharp
- C++
- VB
---

# GetSynchronizationTokenFromAnchorSet Method

Returns an object representing the sync anchor set from a given synchronization token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetSynchronizationTokenFromAnchorSet ( _
    anchorSet As ProductChangeTrackingAnchorSet, _
    marker As Long _
) As Char()
'Usage
Dim anchorSet As ProductChangeTrackingAnchorSet
Dim marker As Long
Dim returnValue As Char()

returnValue = ProductChangeTrackingAnchorSet.GetSynchronizationTokenFromAnchorSet(anchorSet, _
    marker)
```

``` csharp
public static char[] GetSynchronizationTokenFromAnchorSet(
    ProductChangeTrackingAnchorSet anchorSet,
    long marker
)
```

``` c++
public:
static array<wchar_t>^ GetSynchronizationTokenFromAnchorSet(
    ProductChangeTrackingAnchorSet^ anchorSet, 
    long long marker
)
```

#### Parameters

  - anchorSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - marker  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Char](https://technet.microsoft.com/library/k493b04s\(v=ax.60\))\[\]  
An encoding of the object representing the anchor set.  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

