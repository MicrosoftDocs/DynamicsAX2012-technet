---
title: ProductVariantDictionary.ProductVariantsAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantsAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantDictionary.ProductVariantsAsList
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantdictionary.productvariantsaslist(v=AX.60)
ms:contentKeyID: 62210834
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantDictionary.ProductVariantsAsList
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariantsAsList Property

Gets the collection of variants as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property ProductVariantsAsList As ICollection(Of ProductVariant)
    Get
'Usage
Dim instance As ProductVariantDictionary
Dim value As ICollection(Of ProductVariant)

value = instance.ProductVariantsAsList
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductVariant> ProductVariantsAsList { get; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductVariant^>^ ProductVariantsAsList {
    ICollection<ProductVariant^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariantDictionary Class](productvariantdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

