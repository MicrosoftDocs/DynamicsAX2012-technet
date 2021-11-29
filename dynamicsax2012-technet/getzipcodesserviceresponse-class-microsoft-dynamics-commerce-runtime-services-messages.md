---
title: GetZipCodesServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetZipCodesServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetZipCodesServiceResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getzipcodesserviceresponse(v=AX.60)
ms:contentKeyID: 62214513
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetZipCodesServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetZipCodesServiceResponse Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the response associated with the [GetZipCodesServiceRequest](getzipcodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetZipCodesServiceResponse _
    Inherits GetAddressInfoServiceResponse(Of ZipCodeInfo)
'Usage
Dim instance As GetZipCodesServiceResponse
```

``` csharp
[DataContractAttribute]
public class GetZipCodesServiceResponse : GetAddressInfoServiceResponse<ZipCodeInfo>
```

``` c++
[DataContractAttribute]
public ref class GetZipCodesServiceResponse : public GetAddressInfoServiceResponse<ZipCodeInfo^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\<[ZipCodeInfo](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetZipCodesServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

