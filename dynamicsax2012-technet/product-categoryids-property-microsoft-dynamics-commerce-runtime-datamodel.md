---
title: Product.CategoryIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.CategoryIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.categoryids(v=AX.60)
ms:contentKeyID: 62208146
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.CategoryIds
dev_langs:
- CSharp
- C++
- VB
---

# CategoryIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the set of category identifiers mapped to this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CategoryIds As ICollection(Of Long)
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As ICollection(Of Long)

value = instance.CategoryIds
```

``` csharp
[DataMemberAttribute]
public ICollection<long> CategoryIds { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<long long>^ CategoryIds {
    ICollection<long long>^ get ();
    internal: void set (ICollection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

