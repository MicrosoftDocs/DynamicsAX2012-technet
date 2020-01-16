---
title: GetZipCodesServiceResponse Constructor (IEnumerable(ZipCodeInfo)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetZipCodesServiceResponse Constructor (IEnumerable(ZipCodeInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetZipCodesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getzipcodesserviceresponse.getzipcodesserviceresponse(v=AX.60)
ms:contentKeyID: 62210611
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetZipCodesServiceResponse Constructor (IEnumerable(ZipCodeInfo))

Initializes a new instance of the [GetZipCodesServiceResponse](getzipcodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    zipCodes As IEnumerable(Of ZipCodeInfo) _
)
'Usage
Dim zipCodes As IEnumerable(Of ZipCodeInfo)

Dim instance As New GetZipCodesServiceResponse(zipCodes)
```

``` csharp
public GetZipCodesServiceResponse(
    IEnumerable<ZipCodeInfo> zipCodes
)
```

``` c++
public:
GetZipCodesServiceResponse(
    IEnumerable<ZipCodeInfo^>^ zipCodes
)
```

#### Parameters

  - zipCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ZipCodeInfo](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetZipCodesServiceResponse Class](getzipcodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetZipCodesServiceResponse Overload](getzipcodesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

