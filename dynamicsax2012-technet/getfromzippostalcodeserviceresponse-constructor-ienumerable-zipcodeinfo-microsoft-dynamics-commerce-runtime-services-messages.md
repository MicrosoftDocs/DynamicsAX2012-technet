---
title: GetFromZipPostalCodeServiceResponse Constructor (IEnumerable(ZipCodeInfo)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetFromZipPostalCodeServiceResponse Constructor (IEnumerable(ZipCodeInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFromZipPostalCodeServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getfromzippostalcodeserviceresponse.getfromzippostalcodeserviceresponse(v=AX.60)
ms:contentKeyID: 62210528
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetFromZipPostalCodeServiceResponse Constructor (IEnumerable(ZipCodeInfo))

Initializes a new instance of the [GetFromZipPostalCodeServiceResponse](getfromzippostalcodeserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

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

Dim instance As New GetFromZipPostalCodeServiceResponse(zipCodes)
```

``` csharp
public GetFromZipPostalCodeServiceResponse(
    IEnumerable<ZipCodeInfo> zipCodes
)
```

``` c++
public:
GetFromZipPostalCodeServiceResponse(
    IEnumerable<ZipCodeInfo^>^ zipCodes
)
```

#### Parameters

  - zipCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ZipCodeInfo](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetFromZipPostalCodeServiceResponse Class](getfromzippostalcodeserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetFromZipPostalCodeServiceResponse Overload](getfromzippostalcodeserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

