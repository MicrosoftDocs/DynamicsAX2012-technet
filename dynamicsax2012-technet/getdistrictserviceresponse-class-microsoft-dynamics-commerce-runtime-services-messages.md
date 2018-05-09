---
title: GetDistrictServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetDistrictServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDistrictServiceResponse
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getdistrictserviceresponse(v=AX.60)
ms:contentKeyID: 62211155
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDistrictServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetDistrictServiceResponse Class

Represents the response for the [GetDistrictServiceRequest](getdistrictservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetDistrictServiceResponse _
    Inherits GetAddressInfoServiceResponse(Of DistrictInfo)
'Usage
Dim instance As GetDistrictServiceResponse
```

``` csharp
[DataContractAttribute]
public class GetDistrictServiceResponse : GetAddressInfoServiceResponse<DistrictInfo>
```

``` c++
[DataContractAttribute]
public ref class GetDistrictServiceResponse : public GetAddressInfoServiceResponse<DistrictInfo^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\<[DistrictInfo](districtinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDistrictServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

