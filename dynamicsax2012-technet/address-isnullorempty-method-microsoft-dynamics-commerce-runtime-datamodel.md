---
title: Address.IsNullOrEmpty Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsNullOrEmpty Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.IsNullOrEmpty(Microsoft.Dynamics.Commerce.Runtime.DataModel.Address)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.isnullorempty(v=AX.60)
ms:contentKeyID: 62209144
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.IsNullOrEmpty
dev_langs:
- CSharp
- C++
- VB
---

# IsNullOrEmpty Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks if an address is null or empty.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsNullOrEmpty ( _
    address As Address _
) As Boolean
'Usage
Dim address As Address
Dim returnValue As Boolean

returnValue = Address.IsNullOrEmpty(address)
```

``` csharp
public static bool IsNullOrEmpty(
    Address address
)
```

``` c++
public:
static bool IsNullOrEmpty(
    Address^ address
)
```

#### Parameters

  - address  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether the address is null or empty.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

