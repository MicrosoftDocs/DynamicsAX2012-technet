---
title: ProductVariantInformation.AddDimensionValue Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddDimensionValue Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.AddDimensionValue(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantinformation.adddimensionvalue(v=AX.60)
ms:contentKeyID: 65317407
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.AddDimensionValue
dev_langs:
- CSharp
- C++
- VB
---

# AddDimensionValue Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddDimensionValue ( _
    variantId As Long, _
    dimension As ProductProperty _
)
'Usage
Dim instance As ProductVariantInformation
Dim variantId As Long
Dim dimension As ProductProperty

instance.AddDimensionValue(variantId, _
    dimension)
```

``` csharp
public void AddDimensionValue(
    long variantId,
    ProductProperty dimension
)
```

``` c++
public:
void AddDimensionValue(
    long long variantId, 
    ProductProperty^ dimension
)
```

#### Parameters

  - variantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - dimension  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductVariantInformation Class](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

