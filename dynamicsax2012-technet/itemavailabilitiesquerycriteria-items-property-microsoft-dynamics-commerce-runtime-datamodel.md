---
title: ItemAvailabilitiesQueryCriteria.Items Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Items Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.Items
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.items(v=AX.60)
ms:contentKeyID: 65320248
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the items. If DataLevel more than Standard query will return quantities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Items As IEnumerable(Of ItemVariantInventoryDimension)
    Get
    Private Set
'Usage
Dim instance As ItemAvailabilitiesQueryCriteria
Dim value As IEnumerable(Of ItemVariantInventoryDimension)

value = instance.Items
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemVariantInventoryDimension> Items { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemVariantInventoryDimension^>^ Items {
    IEnumerable<ItemVariantInventoryDimension^>^ get ();
    private: void set (IEnumerable<ItemVariantInventoryDimension^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

