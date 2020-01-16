---
title: ProductToKitVariantDictionary.ProductToKitVariantDictionaryAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductToKitVariantDictionaryAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductToKitVariantDictionary.ProductToKitVariantDictionaryAsList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.producttokitvariantdictionary.producttokitvariantdictionaryaslist(v=AX.60)
ms:contentKeyID: 62203258
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductToKitVariantDictionary.ProductToKitVariantDictionaryAsList
dev_langs:
- CSharp
- C++
- VB
---

# ProductToKitVariantDictionaryAsList Property

Gets a flat listed collection of kitlineproducts to kitvariant associations ([ComponentKitVariantSet](componentkitvariantset-class-microsoft-dynamics-commerce-runtime-datamodel.md) objects).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property ProductToKitVariantDictionaryAsList As ICollection(Of ComponentKitVariantSet)
    Get
'Usage
Dim instance As ProductToKitVariantDictionary
Dim value As ICollection(Of ComponentKitVariantSet)

value = instance.ProductToKitVariantDictionaryAsList
```

``` csharp
public ICollection<ComponentKitVariantSet> ProductToKitVariantDictionaryAsList { get; }
```

``` c++
public:
property ICollection<ComponentKitVariantSet^>^ ProductToKitVariantDictionaryAsList {
    ICollection<ComponentKitVariantSet^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ComponentKitVariantSet](componentkitvariantset-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductToKitVariantDictionary Class](producttokitvariantdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

