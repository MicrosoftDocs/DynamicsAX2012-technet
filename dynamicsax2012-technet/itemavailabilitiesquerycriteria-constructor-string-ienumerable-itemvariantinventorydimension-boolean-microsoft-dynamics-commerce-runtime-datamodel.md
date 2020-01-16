---
title: ItemAvailabilitiesQueryCriteria Constructor (String, IEnumerable(ItemVariantInventoryDimension), Boolean) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemAvailabilitiesQueryCriteria Constructor (String, IEnumerable(ItemVariantInventoryDimension), Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.itemavailabilitiesquerycriteria(v=AX.60)
ms:contentKeyID: 65319901
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemAvailabilitiesQueryCriteria Constructor (String, IEnumerable(ItemVariantInventoryDimension), Boolean)

Initializes a new instance of the [ItemAvailabilitiesQueryCriteria](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md) class for the GetItemAvailabilitiesByItems or GetItemAvailableQuantitiesByItems call.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customerAccountNumber As String, _
    items As IEnumerable(Of ItemVariantInventoryDimension), _
    includeQuantities As Boolean _
)
'Usage
Dim customerAccountNumber As String
Dim items As IEnumerable(Of ItemVariantInventoryDimension)
Dim includeQuantities As Boolean

Dim instance As New ItemAvailabilitiesQueryCriteria(customerAccountNumber, _
    items, includeQuantities)
```

``` csharp
public ItemAvailabilitiesQueryCriteria(
    string customerAccountNumber,
    IEnumerable<ItemVariantInventoryDimension> items,
    bool includeQuantities
)
```

``` c++
public:
ItemAvailabilitiesQueryCriteria(
    String^ customerAccountNumber, 
    IEnumerable<ItemVariantInventoryDimension^>^ items, 
    bool includeQuantities
)
```

#### Parameters

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - includeQuantities  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ItemAvailabilitiesQueryCriteria Overload](itemavailabilitiesquerycriteria-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

