---
title: GetItemAvailabilitiesBaseServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetItemAvailabilitiesBaseServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesBaseServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbaseserviceresponse.getitemavailabilitiesbaseserviceresponse(v=AX.60)
ms:contentKeyID: 62213891
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesBaseServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesBaseServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetItemAvailabilitiesBaseServiceResponse](getitemavailabilitiesbaseserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    itemAvailabilities As IEnumerable(Of ItemAvailability), _
    totalNumberOfRecords As Integer _
)
'Usage
Dim itemAvailabilities As IEnumerable(Of ItemAvailability)
Dim totalNumberOfRecords As Integer

Dim instance As New GetItemAvailabilitiesBaseServiceResponse(itemAvailabilities, _
    totalNumberOfRecords)
```

``` csharp
protected GetItemAvailabilitiesBaseServiceResponse(
    IEnumerable<ItemAvailability> itemAvailabilities,
    int totalNumberOfRecords
)
```

``` c++
protected:
GetItemAvailabilitiesBaseServiceResponse(
    IEnumerable<ItemAvailability^>^ itemAvailabilities, 
    int totalNumberOfRecords
)
```

#### Parameters

  - itemAvailabilities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - totalNumberOfRecords  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetItemAvailabilitiesBaseServiceResponse Class](getitemavailabilitiesbaseserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

