---
title: GetStoreLocationsResponse Constructor (IEnumerable(OrgUnitLocation), Int32) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoreLocationsResponse Constructor (IEnumerable(OrgUnitLocation), Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstorelocationsresponse.getstorelocationsresponse(v=AX.60)
ms:contentKeyID: 62208984
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreLocationsResponse Constructor (IEnumerable(OrgUnitLocation), Int32)

Initializes a new instance of the [GetStoreLocationsResponse](getstorelocationsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    storeLocations As IEnumerable(Of OrgUnitLocation), _
    totalNumberOfRecords As Integer _
)
'Usage
Dim storeLocations As IEnumerable(Of OrgUnitLocation)
Dim totalNumberOfRecords As Integer

Dim instance As New GetStoreLocationsResponse(storeLocations, _
    totalNumberOfRecords)
```

``` csharp
public GetStoreLocationsResponse(
    IEnumerable<OrgUnitLocation> storeLocations,
    int totalNumberOfRecords
)
```

``` c++
public:
GetStoreLocationsResponse(
    IEnumerable<OrgUnitLocation^>^ storeLocations, 
    int totalNumberOfRecords
)
```

#### Parameters

  - storeLocations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - totalNumberOfRecords  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetStoreLocationsResponse Class](getstorelocationsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoreLocationsResponse Overload](getstorelocationsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

