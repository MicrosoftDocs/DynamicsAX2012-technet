---
title: Product.GetVariants Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetVariants Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetVariants
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.getvariants(v=AX.60)
ms:contentKeyID: 62203653
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetVariants
dev_langs:
- CSharp
- C++
- VB
---

# GetVariants Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Enumerates a product's variants.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetVariants As ReadOnlyCollection(Of ProductVariant)
'Usage
Dim instance As Product
Dim returnValue As ReadOnlyCollection(Of ProductVariant)

returnValue = instance.GetVariants()
```

``` csharp
public ReadOnlyCollection<ProductVariant> GetVariants()
```

``` c++
public:
ReadOnlyCollection<ProductVariant^>^ GetVariants()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A list of product variant objects.  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

