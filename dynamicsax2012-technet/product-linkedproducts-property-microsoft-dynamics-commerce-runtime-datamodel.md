---
title: Product.LinkedProducts Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LinkedProducts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.LinkedProducts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.linkedproducts(v=AX.60)
ms:contentKeyID: 62210754
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.LinkedProducts
dev_langs:
- CSharp
- C++
- VB
---

# LinkedProducts Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets information about the products linked to this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LinkedProducts As ICollection(Of LinkedProduct)
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As ICollection(Of LinkedProduct)

value = instance.LinkedProducts
```

``` csharp
[DataMemberAttribute]
public ICollection<LinkedProduct> LinkedProducts { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<LinkedProduct^>^ LinkedProducts {
    ICollection<LinkedProduct^>^ get ();
    internal: void set (ICollection<LinkedProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

