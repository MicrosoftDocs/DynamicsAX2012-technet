---
title: CommercePropertyValue.FromObject Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromObject Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.FromObject(System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.fromobject(v=AX.60)
ms:contentKeyID: 62206745
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.FromObject
dev_langs:
- CSharp
- C++
- VB
---

# FromObject Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Defines explicit object-to-CommercePropertyValue conversion method.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function FromObject ( _
    value As Object _
) As CommercePropertyValue
'Usage
Dim value As Object
Dim returnValue As CommercePropertyValue

returnValue = CommercePropertyValue.FromObject(value)
```

``` csharp
public static CommercePropertyValue FromObject(
    Object value
)
```

``` c++
public:
static CommercePropertyValue^ FromObject(
    Object^ value
)
```

#### Parameters

  - value  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The commerce property value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

