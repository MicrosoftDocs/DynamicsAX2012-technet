---
title: KitDefinition.IndexedProductToKitVariantMap Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedProductToKitVariantMap Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.IndexedProductToKitVariantMap
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.kitdefinition.indexedproducttokitvariantmap(v=AX.60)
ms:contentKeyID: 62213209
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.IndexedProductToKitVariantMap
dev_langs:
- CSharp
- C++
- VB
---

# IndexedProductToKitVariantMap Property

Gets a list of kit related properties of all products used in the kit as component or substitutes, indexed by the kitline identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedProductToKitVariantMap As ProductToKitVariantDictionary
    Get
    Friend Set
'Usage
Dim instance As KitDefinition
Dim value As ProductToKitVariantDictionary

value = instance.IndexedProductToKitVariantMap
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductToKitVariantDictionary IndexedProductToKitVariantMap { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductToKitVariantDictionary^ IndexedProductToKitVariantMap {
    ProductToKitVariantDictionary^ get ();
    internal: void set (ProductToKitVariantDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductToKitVariantDictionary](producttokitvariantdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductToKitVariantDictionary](producttokitvariantdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[KitDefinition Class](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

