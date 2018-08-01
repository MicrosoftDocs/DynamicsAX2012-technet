---
title: CommercePropertyValue Implicit Conversion (Int32 to CommercePropertyValue) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Implicit Conversion (Int32 to CommercePropertyValue)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.op_Implicit(System.Int32)~Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.op_implicit(v=AX.60)
ms:contentKeyID: 62210061
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Implicit Conversion (Int32 to CommercePropertyValue)

Defines implicit int-to-CommercePropertyValue conversion operator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Widening Operator CType ( _
    value As Integer _
) As CommercePropertyValue
'Usage
Dim input As Integer
Dim output As CommercePropertyValue

output = CType(input, CommercePropertyValue)
```

``` csharp
public static implicit operator CommercePropertyValue (
    int value
)
```

``` c++
static implicit operator CommercePropertyValue^ (
    int value
)
```

#### Parameters

  - value  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The commerce property value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Implicit Overload](commercepropertyvalue-implicit-conversion-operators-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

