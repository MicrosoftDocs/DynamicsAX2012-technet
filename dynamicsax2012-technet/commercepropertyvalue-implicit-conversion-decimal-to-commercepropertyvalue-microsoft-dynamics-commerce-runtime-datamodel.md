---
title: CommercePropertyValue Implicit Conversion (Decimal to CommercePropertyValue) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Implicit Conversion (Decimal to CommercePropertyValue)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.op_Implicit(System.Decimal)~Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.op_implicit(v=AX.60)
ms:contentKeyID: 62212061
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Implicit Conversion (Decimal to CommercePropertyValue)

Defines implicit decimal-to-CommercePropertyValue conversion operator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Widening Operator CType ( _
    value As Decimal _
) As CommercePropertyValue
'Usage
Dim input As Decimal
Dim output As CommercePropertyValue

output = CType(input, CommercePropertyValue)
```

``` csharp
public static implicit operator CommercePropertyValue (
    decimal value
)
```

``` c++
static implicit operator CommercePropertyValue^ (
    Decimal value
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The commerce property value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Implicit Overload](commercepropertyvalue-implicit-conversion-operators-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

