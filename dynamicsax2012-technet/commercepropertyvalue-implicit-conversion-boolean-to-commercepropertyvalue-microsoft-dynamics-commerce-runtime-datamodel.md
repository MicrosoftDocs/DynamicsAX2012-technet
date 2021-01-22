---
title: CommercePropertyValue Implicit Conversion (Boolean to CommercePropertyValue) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Implicit Conversion (Boolean to CommercePropertyValue)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.op_Implicit(System.Boolean)~Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.op_implicit(v=AX.60)
ms:contentKeyID: 62209231
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Implicit Conversion (Boolean to CommercePropertyValue)

Defines implicit bool-to-CommercePropertyValue conversion operator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Widening Operator CType ( _
    value As Boolean _
) As CommercePropertyValue
'Usage
Dim input As Boolean
Dim output As CommercePropertyValue

output = CType(input, CommercePropertyValue)
```

``` csharp
public static implicit operator CommercePropertyValue (
    bool value
)
```

``` c++
static implicit operator CommercePropertyValue^ (
    bool value
)
```

#### Parameters

  - value  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The commerce property value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Implicit Overload](commercepropertyvalue-implicit-conversion-operators-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

