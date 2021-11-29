---
title: ItemAvailabilitiesQueryCriteria Constructor (IEnumerable(ItemQuantity), String, Int32) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemAvailabilitiesQueryCriteria Constructor (IEnumerable(ItemQuantity), String, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity},System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.itemavailabilitiesquerycriteria(v=AX.60)
ms:contentKeyID: 65317571
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemAvailabilitiesQueryCriteria Constructor (IEnumerable(ItemQuantity), String, Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ItemAvailabilitiesQueryCriteria](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md) class for the GetItemAvailabilitiesByItemQuantities call.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemQuantities As IEnumerable(Of ItemQuantity), _
    customerAccountNumber As String, _
    maxWarehousesPerItem As Integer _
)
'Usage
Dim itemQuantities As IEnumerable(Of ItemQuantity)
Dim customerAccountNumber As String
Dim maxWarehousesPerItem As Integer

Dim instance As New ItemAvailabilitiesQueryCriteria(itemQuantities, _
    customerAccountNumber, maxWarehousesPerItem)
```

``` csharp
public ItemAvailabilitiesQueryCriteria(
    IEnumerable<ItemQuantity> itemQuantities,
    string customerAccountNumber,
    int maxWarehousesPerItem
)
```

``` c++
public:
ItemAvailabilitiesQueryCriteria(
    IEnumerable<ItemQuantity^>^ itemQuantities, 
    String^ customerAccountNumber, 
    int maxWarehousesPerItem
)
```

#### Parameters

  - itemQuantities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maxWarehousesPerItem  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ItemAvailabilitiesQueryCriteria Overload](itemavailabilitiesquerycriteria-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

