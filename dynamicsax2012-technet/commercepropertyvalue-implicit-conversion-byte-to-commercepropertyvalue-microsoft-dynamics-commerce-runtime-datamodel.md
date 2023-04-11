---
title: CommercePropertyValue Implicit Conversion (Byte to CommercePropertyValue) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Implicit Conversion (Byte to CommercePropertyValue)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.op_Implicit(System.Byte)~Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.op_implicit(v=AX.60)
ms:contentKeyID: 62214346
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Implicit Conversion (Byte to CommercePropertyValue)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Defines implicit byte-to-CommercePropertyValue conversion operator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Widening Operator CType ( _
    value As Byte _
) As CommercePropertyValue
'Usage
Dim input As Byte
Dim output As CommercePropertyValue

output = CType(input, CommercePropertyValue)
```

``` csharp
public static implicit operator CommercePropertyValue (
    byte value
)
```

``` c++
static implicit operator CommercePropertyValue^ (
    unsigned char value
)
```

#### Parameters

  - value  
    Type: [System.Byte](https://msdn.microsoft.com/library/yyb1w04y\(v=ax.60\)) 

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The commerce property value.  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Implicit Overload](commercepropertyvalue-implicit-conversion-operators-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

