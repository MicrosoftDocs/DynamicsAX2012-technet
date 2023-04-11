---
title: GetFromZipPostalCodeServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetFromZipPostalCodeServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFromZipPostalCodeServiceResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getfromzippostalcodeserviceresponse(v=AX.60)
ms:contentKeyID: 62213629
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFromZipPostalCodeServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetFromZipPostalCodeServiceResponse Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the resposne for the [GetFromZipPostalCodeServiceRequest](getfromzippostalcodeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetFromZipPostalCodeServiceResponse _
    Inherits GetAddressInfoServiceResponse(Of ZipCodeInfo)
'Usage
Dim instance As GetFromZipPostalCodeServiceResponse
```

``` csharp
[DataContractAttribute]
public class GetFromZipPostalCodeServiceResponse : GetAddressInfoServiceResponse<ZipCodeInfo>
```

``` c++
[DataContractAttribute]
public ref class GetFromZipPostalCodeServiceResponse : public GetAddressInfoServiceResponse<ZipCodeInfo^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\<[ZipCodeInfo](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFromZipPostalCodeServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

