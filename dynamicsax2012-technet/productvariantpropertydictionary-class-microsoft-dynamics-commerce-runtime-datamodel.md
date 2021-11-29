---
title: ProductVariantPropertyDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantPropertyDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertyDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantpropertydictionary(v=AX.60)
ms:contentKeyID: 62207639
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertyDictionary
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariantPropertyDictionary Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents all the properties of a given product and its eventual variants, keyed by their unique product identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "ProductVariantPropertyDictionary", ItemName := "Entry",  _
    KeyName := "VariantId", ValueName := "ProductPropertyTranslationDictionary")> _
Public NotInheritable Class ProductVariantPropertyDictionary _
    Inherits Dictionary(Of Long, ProductPropertyTranslationDictionary)
'Usage
Dim instance As ProductVariantPropertyDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "ProductVariantPropertyDictionary", ItemName = "Entry", 
    KeyName = "VariantId", ValueName = "ProductPropertyTranslationDictionary")]
public sealed class ProductVariantPropertyDictionary : Dictionary<long, ProductPropertyTranslationDictionary>
```

``` c++
[CollectionDataContractAttribute(Name = L"ProductVariantPropertyDictionary", ItemName = L"Entry", 
    KeyName = L"VariantId", ValueName = L"ProductPropertyTranslationDictionary")]
public ref class ProductVariantPropertyDictionary sealed : public Dictionary<long long, ProductPropertyTranslationDictionary^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [ProductPropertyTranslationDictionary](productpropertytranslationdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertyDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

