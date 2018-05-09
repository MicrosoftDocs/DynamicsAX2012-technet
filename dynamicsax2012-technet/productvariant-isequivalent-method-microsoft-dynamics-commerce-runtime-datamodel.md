---
title: ProductVariant.IsEquivalent Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsEquivalent Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.IsEquivalent(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.isequivalent(v=AX.60)
ms:contentKeyID: 62210416
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.IsEquivalent
dev_langs:
- CSharp
- C++
- VB
---

# IsEquivalent Method

Determines whether the specified variant is equivalent to this variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function IsEquivalent ( _
    otherValue As ProductVariant _
) As Boolean
'Usage
Dim instance As ProductVariant
Dim otherValue As ProductVariant
Dim returnValue As Boolean

returnValue = instance.IsEquivalent(otherValue)
```

``` csharp
public bool IsEquivalent(
    ProductVariant otherValue
)
```

``` c++
public:
bool IsEquivalent(
    ProductVariant^ otherValue
)
```

#### Parameters

  - otherValue  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
A value indicating whether the two variants are equivalent.  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

