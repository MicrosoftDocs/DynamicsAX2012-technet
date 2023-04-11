---
title: ProductDimensionSet.DimensionValues Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DimensionValues Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionSet.DimensionValues
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensionset.dimensionvalues(v=AX.60)
ms:contentKeyID: 62205883
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionSet.DimensionValues
dev_langs:
- CSharp
- C++
- VB
---

# DimensionValues Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the set of values of this dimension as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property DimensionValues As ICollection(Of ProductDimensionValueSet)
    Get
'Usage
Dim instance As ProductDimensionSet
Dim value As ICollection(Of ProductDimensionValueSet)

value = instance.DimensionValues
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductDimensionValueSet> DimensionValues { get; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductDimensionValueSet^>^ DimensionValues {
    ICollection<ProductDimensionValueSet^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductDimensionValueSet](productdimensionvalueset-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductDimensionSet Class](productdimensionset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

