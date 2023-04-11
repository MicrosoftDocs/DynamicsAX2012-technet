---
title: ProductVariantInformation.Variants Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Variants Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.Variants
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantinformation.variants(v=AX.60)
ms:contentKeyID: 62211597
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.Variants
dev_langs:
- CSharp
- C++
- VB
---

# Variants Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the properties of the variants of this product as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Variants As ICollection(Of ProductVariant)
    Get
    Friend Set
'Usage
Dim instance As ProductVariantInformation
Dim value As ICollection(Of ProductVariant)

value = instance.Variants
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductVariant> Variants { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductVariant^>^ Variants {
    ICollection<ProductVariant^>^ get ();
    internal: void set (ICollection<ProductVariant^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariantInformation Class](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

