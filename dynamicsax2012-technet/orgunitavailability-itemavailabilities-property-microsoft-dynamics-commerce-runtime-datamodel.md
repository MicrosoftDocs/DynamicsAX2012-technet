---
title: OrgUnitAvailability.ItemAvailabilities Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemAvailabilities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitAvailability.ItemAvailabilities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitavailability.itemavailabilities(v=AX.60)
ms:contentKeyID: 62214461
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitAvailability.ItemAvailabilities
dev_langs:
- CSharp
- C++
- VB
---

# ItemAvailabilities Property

Gets or sets the collection of [ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemAvailabilities As IEnumerable(Of ItemAvailability)
    Get
    Set
'Usage
Dim instance As OrgUnitAvailability
Dim value As IEnumerable(Of ItemAvailability)

value = instance.ItemAvailabilities

instance.ItemAvailabilities = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemAvailability> ItemAvailabilities { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemAvailability^>^ ItemAvailabilities {
    IEnumerable<ItemAvailability^>^ get ();
    void set (IEnumerable<ItemAvailability^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitAvailability Class](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

