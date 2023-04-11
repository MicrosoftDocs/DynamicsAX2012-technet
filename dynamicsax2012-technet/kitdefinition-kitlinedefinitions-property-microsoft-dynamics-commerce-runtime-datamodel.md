---
title: KitDefinition.KitLineDefinitions Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitLineDefinitions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.KitLineDefinitions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitdefinition.kitlinedefinitions(v=AX.60)
ms:contentKeyID: 62212595
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.KitLineDefinitions
dev_langs:
- CSharp
- C++
- VB
---

# KitLineDefinitions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all possible substitutable unique products for the current kit component line.

If the substitutes are variants of the same product master, only the product master is saved in this list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitLineDefinitions As ICollection(Of KitLineDefinition)
    Get
    Friend Set
'Usage
Dim instance As KitDefinition
Dim value As ICollection(Of KitLineDefinition)

value = instance.KitLineDefinitions
```

``` csharp
[DataMemberAttribute]
public ICollection<KitLineDefinition> KitLineDefinitions { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<KitLineDefinition^>^ KitLineDefinitions {
    ICollection<KitLineDefinition^>^ get ();
    internal: void set (ICollection<KitLineDefinition^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[KitLineDefinition](kitlinedefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[KitDefinition Class](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

