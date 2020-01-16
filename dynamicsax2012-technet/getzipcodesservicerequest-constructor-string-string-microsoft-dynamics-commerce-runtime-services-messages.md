---
title: GetZipCodesServiceRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetZipCodesServiceRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetZipCodesServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getzipcodesservicerequest.getzipcodesservicerequest(v=AX.60)
ms:contentKeyID: 65320627
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetZipCodesServiceRequest Constructor (String, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionId As String, _
    stateId As String _
)
'Usage
Dim countryRegionId As String
Dim stateId As String

Dim instance As New GetZipCodesServiceRequest(countryRegionId, _
    stateId)
```

``` csharp
public GetZipCodesServiceRequest(
    string countryRegionId,
    string stateId
)
```

``` c++
public:
GetZipCodesServiceRequest(
    String^ countryRegionId, 
    String^ stateId
)
```

#### Parameters

  - countryRegionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stateId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetZipCodesServiceRequest Class](getzipcodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetZipCodesServiceRequest Overload](getzipcodesservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

