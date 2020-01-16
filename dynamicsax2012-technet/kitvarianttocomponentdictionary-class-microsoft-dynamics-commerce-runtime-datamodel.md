---
title: KitVariantToComponentDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitVariantToComponentDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantToComponentDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitvarianttocomponentdictionary(v=AX.60)
ms:contentKeyID: 62211958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantToComponentDictionary
dev_langs:
- CSharp
- C++
- VB
---

# KitVariantToComponentDictionary Class

Represents a collection of [KitVariantContent](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md) indexed by the kit variant Ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "KitVariantToComponentDictionary", ItemName := "Entry",  _
    KeyName := "KitVariantId", ValueName := "KitVariantDetail")> _
Public NotInheritable Class KitVariantToComponentDictionary _
    Inherits Dictionary(Of Long, KitVariantContent)
'Usage
Dim instance As KitVariantToComponentDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "KitVariantToComponentDictionary", ItemName = "Entry", 
    KeyName = "KitVariantId", ValueName = "KitVariantDetail")]
public sealed class KitVariantToComponentDictionary : Dictionary<long, KitVariantContent>
```

``` c++
[CollectionDataContractAttribute(Name = L"KitVariantToComponentDictionary", ItemName = L"Entry", 
    KeyName = L"KitVariantId", ValueName = L"KitVariantDetail")]
public ref class KitVariantToComponentDictionary sealed : public Dictionary<long long, KitVariantContent^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [KitVariantContent](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantToComponentDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

