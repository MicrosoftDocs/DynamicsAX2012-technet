---
title: CommercePropertyValue Explicit Conversion (CommercePropertyValue to String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Explicit Conversion (CommercePropertyValue to String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.op_Explicit(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue)~System.String
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.op_explicit(v=AX.60)
ms:contentKeyID: 62202310
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Explicit Conversion (CommercePropertyValue to String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Defines explicit CommercePropertyValue-to-string conversion operator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Narrowing Operator CType ( _
    propertyValue As CommercePropertyValue _
) As String
'Usage
Dim input As CommercePropertyValue
Dim output As String

output = CType(input, String)
```

``` csharp
public static explicit operator string (
    CommercePropertyValue propertyValue
)
```

``` c++
static explicit operator String^ (
    CommercePropertyValue^ propertyValue
)
```

#### Parameters

  - propertyValue  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Explicit Overload](commercepropertyvalue-explicit-conversion-operators-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

