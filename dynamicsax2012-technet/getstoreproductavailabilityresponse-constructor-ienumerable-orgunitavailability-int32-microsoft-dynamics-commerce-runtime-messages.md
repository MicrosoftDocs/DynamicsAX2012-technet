---
title: GetStoreProductAvailabilityResponse Constructor (IEnumerable(OrgUnitAvailability), Int32) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoreProductAvailabilityResponse Constructor (IEnumerable(OrgUnitAvailability), Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitAvailability},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoreproductavailabilityresponse.getstoreproductavailabilityresponse(v=AX.60)
ms:contentKeyID: 62213379
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreProductAvailabilityResponse Constructor (IEnumerable(OrgUnitAvailability), Int32)

Initializes a new instance of the [GetStoreProductAvailabilityResponse](getstoreproductavailabilityresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    storeAvailabilities As IEnumerable(Of OrgUnitAvailability), _
    totalNumberOfRecords As Integer _
)
'Usage
Dim storeAvailabilities As IEnumerable(Of OrgUnitAvailability)
Dim totalNumberOfRecords As Integer

Dim instance As New GetStoreProductAvailabilityResponse(storeAvailabilities, _
    totalNumberOfRecords)
```

``` csharp
public GetStoreProductAvailabilityResponse(
    IEnumerable<OrgUnitAvailability> storeAvailabilities,
    int totalNumberOfRecords
)
```

``` c++
public:
GetStoreProductAvailabilityResponse(
    IEnumerable<OrgUnitAvailability^>^ storeAvailabilities, 
    int totalNumberOfRecords
)
```

#### Parameters

  - storeAvailabilities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OrgUnitAvailability](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - totalNumberOfRecords  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetStoreProductAvailabilityResponse Class](getstoreproductavailabilityresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoreProductAvailabilityResponse Overload](getstoreproductavailabilityresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

