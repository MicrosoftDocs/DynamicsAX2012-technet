---
title: KitLineDefinition.ComponentProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ComponentProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.ComponentProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.kitlinedefinition.componentproperties(v=AX.60)
ms:contentKeyID: 62215014
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.ComponentProperties
dev_langs:
- CSharp
- C++
- VB
---

# ComponentProperties Property

Gets the collection of kit related properties of a product as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ComponentProperties As ICollection(Of KitLineProductProperty)
    Get
    Friend Set
'Usage
Dim instance As KitLineDefinition
Dim value As ICollection(Of KitLineProductProperty)

value = instance.ComponentProperties
```

``` csharp
[DataMemberAttribute]
public ICollection<KitLineProductProperty> ComponentProperties { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<KitLineProductProperty^>^ ComponentProperties {
    ICollection<KitLineProductProperty^>^ get ();
    internal: void set (ICollection<KitLineProductProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[KitLineProductProperty](kitlineproductproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[KitLineDefinition Class](kitlinedefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

