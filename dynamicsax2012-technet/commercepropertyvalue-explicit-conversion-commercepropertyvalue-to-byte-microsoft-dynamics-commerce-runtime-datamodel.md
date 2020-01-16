---
title: CommercePropertyValue Explicit Conversion (CommercePropertyValue to Byte) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Explicit Conversion (CommercePropertyValue to Byte)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.op_Explicit(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue)~System.Byte
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.op_explicit(v=AX.60)
ms:contentKeyID: 62203271
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Explicit Conversion (CommercePropertyValue to Byte)

Defines explicit CommercePropertyValue-to-byte conversion operator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Narrowing Operator CType ( _
    propertyValue As CommercePropertyValue _
) As Byte
'Usage
Dim input As CommercePropertyValue
Dim output As Byte

output = CType(input, Byte)
```

``` csharp
public static explicit operator byte (
    CommercePropertyValue propertyValue
)
```

``` c++
static explicit operator unsigned char (
    CommercePropertyValue^ propertyValue
)
```

#### Parameters

  - propertyValue  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))  
The byte value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Explicit Overload](commercepropertyvalue-explicit-conversion-operators-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

