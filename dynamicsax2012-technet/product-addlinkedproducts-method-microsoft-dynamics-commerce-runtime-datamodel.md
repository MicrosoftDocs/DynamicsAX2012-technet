---
title: Product.AddLinkedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddLinkedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.AddLinkedProducts(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.LinkedProduct})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.addlinkedproducts(v=AX.60)
ms:contentKeyID: 65319121
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.AddLinkedProducts
dev_langs:
- CSharp
- C++
- VB
---

# AddLinkedProducts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddLinkedProducts ( _
    linkedProducts As IEnumerable(Of LinkedProduct) _
)
'Usage
Dim instance As Product
Dim linkedProducts As IEnumerable(Of LinkedProduct)

instance.AddLinkedProducts(linkedProducts)
```

``` csharp
public void AddLinkedProducts(
    IEnumerable<LinkedProduct> linkedProducts
)
```

``` c++
public:
void AddLinkedProducts(
    IEnumerable<LinkedProduct^>^ linkedProducts
)
```

#### Parameters

  - linkedProducts  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

