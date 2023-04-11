---
title: GetItemAvailableQuantitiesResponse Constructor (IEnumerable(ItemAvailableQuantity), Int32) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetItemAvailableQuantitiesResponse Constructor (IEnumerable(ItemAvailableQuantity), Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableQuantity},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemavailablequantitiesresponse.getitemavailablequantitiesresponse(v=AX.60)
ms:contentKeyID: 49855549
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemAvailableQuantitiesResponse Constructor (IEnumerable(ItemAvailableQuantity), Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetItemAvailableQuantitiesResponse](getitemavailablequantitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    quantities As IEnumerable(Of ItemAvailableQuantity), _
    totalNumberOfRecords As Integer _
)
'Usage
Dim quantities As IEnumerable(Of ItemAvailableQuantity)
Dim totalNumberOfRecords As Integer

Dim instance As New GetItemAvailableQuantitiesResponse(quantities, _
    totalNumberOfRecords)
```

``` csharp
public GetItemAvailableQuantitiesResponse(
    IEnumerable<ItemAvailableQuantity> quantities,
    int totalNumberOfRecords
)
```

``` c++
public:
GetItemAvailableQuantitiesResponse(
    IEnumerable<ItemAvailableQuantity^>^ quantities, 
    int totalNumberOfRecords
)
```

#### Parameters

  - quantities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemAvailableQuantity](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - totalNumberOfRecords  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetItemAvailableQuantitiesResponse Class](getitemavailablequantitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetItemAvailableQuantitiesResponse Overload](getitemavailablequantitiesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

