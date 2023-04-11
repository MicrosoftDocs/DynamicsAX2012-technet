---
title: KitDefinition.IndexedKitVariantToComponentMap Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedKitVariantToComponentMap Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.IndexedKitVariantToComponentMap
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitdefinition.indexedkitvarianttocomponentmap(v=AX.60)
ms:contentKeyID: 62209546
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.IndexedKitVariantToComponentMap
dev_langs:
- CSharp
- C++
- VB
---

# IndexedKitVariantToComponentMap Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a collection of ([KitVariantContent](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md) objects for the current kit indexed by the kit variant Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedKitVariantToComponentMap As KitVariantToComponentDictionary
    Get
    Friend Set
'Usage
Dim instance As KitDefinition
Dim value As KitVariantToComponentDictionary

value = instance.IndexedKitVariantToComponentMap
```

``` csharp
[IgnoreDataMemberAttribute]
public KitVariantToComponentDictionary IndexedKitVariantToComponentMap { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property KitVariantToComponentDictionary^ IndexedKitVariantToComponentMap {
    KitVariantToComponentDictionary^ get ();
    internal: void set (KitVariantToComponentDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantToComponentDictionary](kitvarianttocomponentdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [KitVariantToComponentDictionary](kitvarianttocomponentdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[KitDefinition Class](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

