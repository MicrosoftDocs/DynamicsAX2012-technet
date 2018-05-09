---
title: CommercePropertyValue Explicit Conversion (CommercePropertyValue to Int64) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Explicit Conversion (CommercePropertyValue to Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.op_Explicit(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue)~System.Int64
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.op_explicit(v=AX.60)
ms:contentKeyID: 62214716
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Explicit Conversion (CommercePropertyValue to Int64)

Defines explicit CommercePropertyValue-to-long conversion operator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Narrowing Operator CType ( _
    propertyValue As CommercePropertyValue _
) As Long
'Usage
Dim input As CommercePropertyValue
Dim output As Long

output = CType(input, Long)
```

``` csharp
public static explicit operator long (
    CommercePropertyValue propertyValue
)
```

``` c++
static explicit operator long long (
    CommercePropertyValue^ propertyValue
)
```

#### Parameters

  - propertyValue  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The long value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Explicit Overload](commercepropertyvalue%C2%A0explicit-conversion-operators-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

