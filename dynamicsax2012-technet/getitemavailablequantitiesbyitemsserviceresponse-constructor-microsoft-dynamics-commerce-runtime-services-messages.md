---
title: GetItemAvailableQuantitiesByItemsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetItemAvailableQuantitiesByItemsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailableQuantitiesByItemsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableQuantity},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailablequantitiesbyitemsserviceresponse.getitemavailablequantitiesbyitemsserviceresponse(v=AX.60)
ms:contentKeyID: 62208485
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailableQuantitiesByItemsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailableQuantitiesByItemsServiceResponse Constructor

Initializes a new instance of the [GetItemAvailableQuantitiesByItemsServiceResponse](getitemavailablequantitiesbyitemsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemAvailableQuantities As IEnumerable(Of ItemAvailableQuantity), _
    totalNumberOfRecords As Integer _
)
'Usage
Dim itemAvailableQuantities As IEnumerable(Of ItemAvailableQuantity)
Dim totalNumberOfRecords As Integer

Dim instance As New GetItemAvailableQuantitiesByItemsServiceResponse(itemAvailableQuantities, _
    totalNumberOfRecords)
```

``` csharp
public GetItemAvailableQuantitiesByItemsServiceResponse(
    IEnumerable<ItemAvailableQuantity> itemAvailableQuantities,
    int totalNumberOfRecords
)
```

``` c++
public:
GetItemAvailableQuantitiesByItemsServiceResponse(
    IEnumerable<ItemAvailableQuantity^>^ itemAvailableQuantities, 
    int totalNumberOfRecords
)
```

#### Parameters

  - itemAvailableQuantities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemAvailableQuantity](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - totalNumberOfRecords  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetItemAvailableQuantitiesByItemsServiceResponse Class](getitemavailablequantitiesbyitemsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

