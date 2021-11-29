---
title: ProductChangeTrackingAnchorSet.AreIdenticalSynchronizationTokens Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AreIdenticalSynchronizationTokens Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.AreIdenticalSynchronizationTokens(System.Char[],System.Char[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.areidenticalsynchronizationtokens(v=AX.60)
ms:contentKeyID: 62212504
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.AreIdenticalSynchronizationTokens
dev_langs:
- CSharp
- C++
- VB
---

# AreIdenticalSynchronizationTokens Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Verifies whether 2o synchronization tokens are equivalent.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function AreIdenticalSynchronizationTokens ( _
    leftSyncToken As Char(), _
    rightSyncToken As Char() _
) As Boolean
'Usage
Dim leftSyncToken As Char()
Dim rightSyncToken As Char()
Dim returnValue As Boolean

returnValue = ProductChangeTrackingAnchorSet.AreIdenticalSynchronizationTokens(leftSyncToken, _
    rightSyncToken)
```

``` csharp
public static bool AreIdenticalSynchronizationTokens(
    char[] leftSyncToken,
    char[] rightSyncToken
)
```

``` c++
public:
static bool AreIdenticalSynchronizationTokens(
    array<wchar_t>^ leftSyncToken, 
    array<wchar_t>^ rightSyncToken
)
```

#### Parameters

  - leftSyncToken  
    Type: [System.Char](https://technet.microsoft.com/library/k493b04s\(v=ax.60\))\[\]  

<!-- end list -->

  - rightSyncToken  
    Type: [System.Char](https://technet.microsoft.com/library/k493b04s\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the 2 sync tokens are equivalent.  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

