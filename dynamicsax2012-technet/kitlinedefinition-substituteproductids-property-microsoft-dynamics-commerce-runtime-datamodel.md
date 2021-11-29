---
title: KitLineDefinition.SubstituteProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SubstituteProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.SubstituteProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitlinedefinition.substituteproductids(v=AX.60)
ms:contentKeyID: 62211978
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.SubstituteProductIds
dev_langs:
- CSharp
- C++
- VB
---

# SubstituteProductIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all possible substitutable products for the current kit component line.

If the substitutes are all variants of the same product master, only the product master is saved in this list, otherwise productvariant ids are saved. This list also includes the product used as a default component in the kit line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SubstituteProductIds As ICollection(Of Long)
    Get
    Friend Set
'Usage
Dim instance As KitLineDefinition
Dim value As ICollection(Of Long)

value = instance.SubstituteProductIds
```

``` csharp
[DataMemberAttribute]
public ICollection<long> SubstituteProductIds { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<long long>^ SubstituteProductIds {
    ICollection<long long>^ get ();
    internal: void set (ICollection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[KitLineDefinition Class](kitlinedefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

