---
title: GetStoresServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetStoresServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getstoresserviceresponse.getstoresserviceresponse(v=AX.60)
ms:contentKeyID: 62213496
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetStoresServiceResponse Constructor

Initializes a new instance of the [GetStoresServiceResponse](getstoresserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    stores As IEnumerable(Of OrgUnitLocation), _
    totalNumberOfRecords As Integer _
)
'Usage
Dim stores As IEnumerable(Of OrgUnitLocation)
Dim totalNumberOfRecords As Integer

Dim instance As New GetStoresServiceResponse(stores, _
    totalNumberOfRecords)
```

``` csharp
public GetStoresServiceResponse(
    IEnumerable<OrgUnitLocation> stores,
    int totalNumberOfRecords
)
```

``` c++
public:
GetStoresServiceResponse(
    IEnumerable<OrgUnitLocation^>^ stores, 
    int totalNumberOfRecords
)
```

#### Parameters

  - stores  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - totalNumberOfRecords  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetStoresServiceResponse Class](getstoresserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

