---
title: GetItemAvailabilitiesByItemWarehousesServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetItemAvailabilitiesByItemWarehousesServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemWarehousesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemwarehousesserviceresponse.getitemavailabilitiesbyitemwarehousesserviceresponse(v=AX.60)
ms:contentKeyID: 62209693
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemWarehousesServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesByItemWarehousesServiceResponse Constructor

Initializes a new instance of the [GetItemAvailabilitiesByItemWarehousesServiceResponse](getitemavailabilitiesbyitemwarehousesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemAvailabilities As IEnumerable(Of ItemAvailability), _
    totalNumberOfRecords As Integer _
)
'Usage
Dim itemAvailabilities As IEnumerable(Of ItemAvailability)
Dim totalNumberOfRecords As Integer

Dim instance As New GetItemAvailabilitiesByItemWarehousesServiceResponse(itemAvailabilities, _
    totalNumberOfRecords)
```

``` csharp
public GetItemAvailabilitiesByItemWarehousesServiceResponse(
    IEnumerable<ItemAvailability> itemAvailabilities,
    int totalNumberOfRecords
)
```

``` c++
public:
GetItemAvailabilitiesByItemWarehousesServiceResponse(
    IEnumerable<ItemAvailability^>^ itemAvailabilities, 
    int totalNumberOfRecords
)
```

#### Parameters

  - itemAvailabilities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - totalNumberOfRecords  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetItemAvailabilitiesByItemWarehousesServiceResponse Class](getitemavailabilitiesbyitemwarehousesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

