---
title: ProductVariantPropertyDictionary.ProductVariantPropertiesAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantPropertiesAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertyDictionary.ProductVariantPropertiesAsList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantpropertydictionary.productvariantpropertiesaslist(v=AX.60)
ms:contentKeyID: 62205151
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertyDictionary.ProductVariantPropertiesAsList
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariantPropertiesAsList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the properties of all the variants of this product as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property ProductVariantPropertiesAsList As ICollection(Of ProductVariantPropertySet)
    Get
'Usage
Dim instance As ProductVariantPropertyDictionary
Dim value As ICollection(Of ProductVariantPropertySet)

value = instance.ProductVariantPropertiesAsList
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductVariantPropertySet> ProductVariantPropertiesAsList { get; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductVariantPropertySet^>^ ProductVariantPropertiesAsList {
    ICollection<ProductVariantPropertySet^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductVariantPropertySet](productvariantpropertyset-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariantPropertyDictionary Class](productvariantpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

