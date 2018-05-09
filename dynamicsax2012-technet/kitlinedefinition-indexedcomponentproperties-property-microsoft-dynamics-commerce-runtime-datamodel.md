---
title: KitLineDefinition.IndexedComponentProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedComponentProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.IndexedComponentProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.kitlinedefinition.indexedcomponentproperties(v=AX.60)
ms:contentKeyID: 62213660
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.IndexedComponentProperties
dev_langs:
- CSharp
- C++
- VB
---

# IndexedComponentProperties Property

Gets a list of kit component properties of all products used in the kit component line as substitute or as a default component product, indexed by the productId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedComponentProperties As KitLineProductPropertyDictionary
    Get
    Friend Set
'Usage
Dim instance As KitLineDefinition
Dim value As KitLineProductPropertyDictionary

value = instance.IndexedComponentProperties
```

``` csharp
[IgnoreDataMemberAttribute]
public KitLineProductPropertyDictionary IndexedComponentProperties { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property KitLineProductPropertyDictionary^ IndexedComponentProperties {
    KitLineProductPropertyDictionary^ get ();
    internal: void set (KitLineProductPropertyDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductPropertyDictionary](kitlineproductpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [KitLineProductPropertyDictionary](kitlineproductpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[KitLineDefinition Class](kitlinedefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

