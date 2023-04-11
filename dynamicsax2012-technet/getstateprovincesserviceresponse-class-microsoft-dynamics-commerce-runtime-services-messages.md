---
title: GetStateProvincesServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetStateProvincesServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStateProvincesServiceResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstateprovincesserviceresponse(v=AX.60)
ms:contentKeyID: 62203095
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStateProvincesServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetStateProvincesServiceResponse Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The resposne associated with the [GetStateProvincesServiceRequest](getstateprovincesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetStateProvincesServiceResponse _
    Inherits GetAddressInfoServiceResponse(Of StateProvinceInfo)
'Usage
Dim instance As GetStateProvincesServiceResponse
```

``` csharp
[DataContractAttribute]
public class GetStateProvincesServiceResponse : GetAddressInfoServiceResponse<StateProvinceInfo>
```

``` c++
[DataContractAttribute]
public ref class GetStateProvincesServiceResponse : public GetAddressInfoServiceResponse<StateProvinceInfo^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\<[StateProvinceInfo](stateprovinceinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStateProvincesServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

