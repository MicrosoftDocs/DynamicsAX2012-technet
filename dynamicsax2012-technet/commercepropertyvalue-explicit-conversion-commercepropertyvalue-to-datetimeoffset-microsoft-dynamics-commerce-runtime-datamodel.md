---
title: CommercePropertyValue Explicit Conversion (CommercePropertyValue to DateTimeOffset) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Explicit Conversion (CommercePropertyValue to DateTimeOffset)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.op_Explicit(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue)~System.DateTimeOffset
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.op_explicit(v=AX.60)
ms:contentKeyID: 62208779
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Explicit Conversion (CommercePropertyValue to DateTimeOffset)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Defines explicit CommercePropertyValue-to-DateTimeOffset conversion operator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Narrowing Operator CType ( _
    propertyValue As CommercePropertyValue _
) As DateTimeOffset
'Usage
Dim input As CommercePropertyValue
Dim output As DateTimeOffset

output = CType(input, DateTimeOffset)
```

``` csharp
public static explicit operator DateTimeOffset (
    CommercePropertyValue propertyValue
)
```

``` c++
static explicit operator DateTimeOffset (
    CommercePropertyValue^ propertyValue
)
```

#### Parameters

  - propertyValue  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
The DateTimeOffset value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Explicit Overload](commercepropertyvalue-explicit-conversion-operators-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

