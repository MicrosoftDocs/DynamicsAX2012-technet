---
title: GetAddressFormattingServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetAddressFormattingServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressFormattingServiceResponse
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getaddressformattingserviceresponse(v=AX.60)
ms:contentKeyID: 62210274
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressFormattingServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetAddressFormattingServiceResponse Class

Represents the resposne for the [GetAddressFormattingServiceRequest](getaddressformattingservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetAddressFormattingServiceResponse _
    Inherits GetAddressInfoServiceResponse(Of AddressFormattingInfo)
'Usage
Dim instance As GetAddressFormattingServiceResponse
```

``` csharp
[DataContractAttribute]
public class GetAddressFormattingServiceResponse : GetAddressInfoServiceResponse<AddressFormattingInfo>
```

``` c++
[DataContractAttribute]
public ref class GetAddressFormattingServiceResponse : public GetAddressInfoServiceResponse<AddressFormattingInfo^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\<[AddressFormattingInfo](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressFormattingServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

