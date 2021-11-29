---
title: ProductVariantPropertySet.ProductVariantPropertiesAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantPropertiesAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertySet.ProductVariantPropertiesAsList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantpropertyset.productvariantpropertiesaslist(v=AX.60)
ms:contentKeyID: 62212157
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertySet.ProductVariantPropertiesAsList
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariantPropertiesAsList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the translated properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property ProductVariantPropertiesAsList As ICollection(Of ProductPropertyTranslation)
    Get
'Usage
Dim instance As ProductVariantPropertySet
Dim value As ICollection(Of ProductPropertyTranslation)

value = instance.ProductVariantPropertiesAsList
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductPropertyTranslation> ProductVariantPropertiesAsList { get; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductPropertyTranslation^>^ ProductVariantPropertiesAsList {
    ICollection<ProductPropertyTranslation^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductPropertyTranslation](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariantPropertySet Class](productvariantpropertyset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

