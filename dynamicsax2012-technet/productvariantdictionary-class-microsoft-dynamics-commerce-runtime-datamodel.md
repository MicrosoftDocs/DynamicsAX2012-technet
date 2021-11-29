---
title: ProductVariantDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantdictionary(v=AX.60)
ms:contentKeyID: 62210963
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantDictionary
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariantDictionary Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a product's variants, keyed on the variant id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "ProductVariantDictionary", ItemName := "Entry",  _
    KeyName := "ProductVariantId", ValueName := "ProductVariant")> _
Public NotInheritable Class ProductVariantDictionary _
    Inherits Dictionary(Of Long, ProductVariant)
'Usage
Dim instance As ProductVariantDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "ProductVariantDictionary", ItemName = "Entry", 
    KeyName = "ProductVariantId", ValueName = "ProductVariant")]
public sealed class ProductVariantDictionary : Dictionary<long, ProductVariant>
```

``` c++
[CollectionDataContractAttribute(Name = L"ProductVariantDictionary", ItemName = L"Entry", 
    KeyName = L"ProductVariantId", ValueName = L"ProductVariant")]
public ref class ProductVariantDictionary sealed : public Dictionary<long long, ProductVariant^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

