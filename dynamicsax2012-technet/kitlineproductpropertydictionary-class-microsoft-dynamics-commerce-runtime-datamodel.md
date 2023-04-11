---
title: KitLineProductPropertyDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitLineProductPropertyDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductPropertyDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitlineproductpropertydictionary(v=AX.60)
ms:contentKeyID: 62215219
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductPropertyDictionary
dev_langs:
- CSharp
- C++
- VB
---

# KitLineProductPropertyDictionary Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the kit related properties of products used in a kit line as a component or substitute, keyed by the productId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "KitLineProductPropertyDictionary", ItemName := "Entry",  _
    KeyName := "KitLineIdentifier", ValueName := "KitLineProductProperty")> _
Public NotInheritable Class KitLineProductPropertyDictionary _
    Inherits Dictionary(Of Long, KitLineProductProperty)
'Usage
Dim instance As KitLineProductPropertyDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "KitLineProductPropertyDictionary", ItemName = "Entry", 
    KeyName = "KitLineIdentifier", ValueName = "KitLineProductProperty")]
public sealed class KitLineProductPropertyDictionary : Dictionary<long, KitLineProductProperty>
```

``` c++
[CollectionDataContractAttribute(Name = L"KitLineProductPropertyDictionary", ItemName = L"Entry", 
    KeyName = L"KitLineIdentifier", ValueName = L"KitLineProductProperty")]
public ref class KitLineProductPropertyDictionary sealed : public Dictionary<long long, KitLineProductProperty^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [KitLineProductProperty](kitlineproductproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductPropertyDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

