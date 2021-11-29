---
title: KitDefinition.KitLineProductToVariantMap Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitLineProductToVariantMap Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.KitLineProductToVariantMap
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitdefinition.kitlineproducttovariantmap(v=AX.60)
ms:contentKeyID: 62202483
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.KitLineProductToVariantMap
dev_langs:
- CSharp
- C++
- VB
---

# KitLineProductToVariantMap Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of kit Line products to kit variant association of the current kit, as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitLineProductToVariantMap As ICollection(Of ComponentKitVariantSet)
    Get
    Friend Set
'Usage
Dim instance As KitDefinition
Dim value As ICollection(Of ComponentKitVariantSet)

value = instance.KitLineProductToVariantMap
```

``` csharp
[DataMemberAttribute]
public ICollection<ComponentKitVariantSet> KitLineProductToVariantMap { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ComponentKitVariantSet^>^ KitLineProductToVariantMap {
    ICollection<ComponentKitVariantSet^>^ get ();
    internal: void set (ICollection<ComponentKitVariantSet^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ComponentKitVariantSet](componentkitvariantset-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[KitDefinition Class](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

