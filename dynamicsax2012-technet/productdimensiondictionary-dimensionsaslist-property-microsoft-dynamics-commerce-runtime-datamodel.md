---
title: ProductDimensionDictionary.DimensionsAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DimensionsAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionDictionary.DimensionsAsList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensiondictionary.dimensionsaslist(v=AX.60)
ms:contentKeyID: 62211314
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionDictionary.DimensionsAsList
dev_langs:
- CSharp
- C++
- VB
---

# DimensionsAsList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of dimensions as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property DimensionsAsList As ICollection(Of ProductDimensionSet)
    Get
'Usage
Dim instance As ProductDimensionDictionary
Dim value As ICollection(Of ProductDimensionSet)

value = instance.DimensionsAsList
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductDimensionSet> DimensionsAsList { get; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductDimensionSet^>^ DimensionsAsList {
    ICollection<ProductDimensionSet^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductDimensionSet](productdimensionset-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductDimensionDictionary Class](productdimensiondictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

