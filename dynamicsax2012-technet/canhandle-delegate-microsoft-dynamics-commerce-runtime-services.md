---
title: CanHandle Delegate (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CanHandle Delegate
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.CanHandle
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.canhandle(v=AX.60)
ms:contentKeyID: 49823118
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CanHandle
dev_langs:
- CSharp
- C++
- VB
---

# CanHandle Delegate

Returns whether or not address can be processed based on the type of filter.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Delegate Function CanHandle ( _
    address As Address _
) As Boolean
'Usage
Dim instance As New CanHandle(AddressOf HandlerMethod)
```

``` csharp
public delegate bool CanHandle(
    Address address
)
```

``` c++
public delegate bool CanHandle(
    Address^ address
)
```

#### Parameters

  - address  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

