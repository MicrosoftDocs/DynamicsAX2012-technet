---
title: ItemAvailabilitiesQueryCriteria Constructor (IEnumerable(ItemWarehouse)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemAvailabilitiesQueryCriteria Constructor (IEnumerable(ItemWarehouse))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemWarehouse})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.itemavailabilitiesquerycriteria(v=AX.60)
ms:contentKeyID: 65321194
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemAvailabilitiesQueryCriteria Constructor (IEnumerable(ItemWarehouse))

Initializes a new instance of the [ItemAvailabilitiesQueryCriteria](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md) class for the GetItemAvailabilitiesByItemWarehouses call.

Get item availabilities by item and warehouse combinations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemWarehouses As IEnumerable(Of ItemWarehouse) _
)
'Usage
Dim itemWarehouses As IEnumerable(Of ItemWarehouse)

Dim instance As New ItemAvailabilitiesQueryCriteria(itemWarehouses)
```

``` csharp
public ItemAvailabilitiesQueryCriteria(
    IEnumerable<ItemWarehouse> itemWarehouses
)
```

``` c++
public:
ItemAvailabilitiesQueryCriteria(
    IEnumerable<ItemWarehouse^>^ itemWarehouses
)
```

#### Parameters

  - itemWarehouses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemWarehouse](itemwarehouse-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ItemAvailabilitiesQueryCriteria Overload](itemavailabilitiesquerycriteria-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

