---
title: CommercePropertyValue.IsSupportedType Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSupportedType Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.IsSupportedType(System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.issupportedtype(v=AX.60)
ms:contentKeyID: 62214574
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.IsSupportedType
dev_langs:
- CSharp
- C++
- VB
---

# IsSupportedType Method

Determines if the type is supported.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsSupportedType ( _
    type As Type _
) As Boolean
'Usage
Dim type As Type
Dim returnValue As Boolean

returnValue = CommercePropertyValue.IsSupportedType(type)
```

``` csharp
public static bool IsSupportedType(
    Type type
)
```

``` c++
public:
static bool IsSupportedType(
    Type^ type
)
```

#### Parameters

  - type  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The boolean to indicate if the type is supported.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

