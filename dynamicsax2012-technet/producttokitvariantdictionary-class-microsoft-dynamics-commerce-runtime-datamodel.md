---
title: ProductToKitVariantDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductToKitVariantDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductToKitVariantDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.producttokitvariantdictionary(v=AX.60)
ms:contentKeyID: 62204934
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductToKitVariantDictionary
dev_langs:
- CSharp
- C++
- VB
---

# ProductToKitVariantDictionary Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a collection of KitLineProductToVariantMaps indexed by the productIds used in the variants.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "ProductToKitVariantDictionary", ItemName := "Entry",  _
    KeyName := "KitLineProductId", ValueName := "ComponentKitVariantSet")> _
Public NotInheritable Class ProductToKitVariantDictionary _
    Inherits Dictionary(Of Long, ComponentKitVariantSet)
'Usage
Dim instance As ProductToKitVariantDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "ProductToKitVariantDictionary", ItemName = "Entry", 
    KeyName = "KitLineProductId", ValueName = "ComponentKitVariantSet")]
public sealed class ProductToKitVariantDictionary : Dictionary<long, ComponentKitVariantSet>
```

``` c++
[CollectionDataContractAttribute(Name = L"ProductToKitVariantDictionary", ItemName = L"Entry", 
    KeyName = L"KitLineProductId", ValueName = L"ComponentKitVariantSet")]
public ref class ProductToKitVariantDictionary sealed : public Dictionary<long long, ComponentKitVariantSet^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [ComponentKitVariantSet](componentkitvariantset-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductToKitVariantDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

