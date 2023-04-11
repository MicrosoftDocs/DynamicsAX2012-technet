---
title: ComponentKitVariantSet.KitVariantIdList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitVariantIdList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ComponentKitVariantSet.KitVariantIdList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.componentkitvariantset.kitvariantidlist(v=AX.60)
ms:contentKeyID: 62206370
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ComponentKitVariantSet.KitVariantIdList
dev_langs:
- CSharp
- C++
- VB
---

# KitVariantIdList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of Kit variant product Ids of a kit, containing the specified kit line product (component).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitVariantIdList As ICollection(Of Long)
    Get
    Friend Set
'Usage
Dim instance As ComponentKitVariantSet
Dim value As ICollection(Of Long)

value = instance.KitVariantIdList
```

``` csharp
[DataMemberAttribute]
public ICollection<long> KitVariantIdList { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<long long>^ KitVariantIdList {
    ICollection<long long>^ get ();
    internal: void set (ICollection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ComponentKitVariantSet Class](componentkitvariantset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

