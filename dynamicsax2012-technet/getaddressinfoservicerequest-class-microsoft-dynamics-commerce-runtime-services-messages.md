---
title: GetAddressInfoServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetAddressInfoServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getaddressinfoservicerequest(v=AX.60)
ms:contentKeyID: 62215094
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# GetAddressInfoServiceRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

GetAddressInfoRequest: base class for enumeration scenarios.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class GetAddressInfoServiceRequest _
    Inherits ServiceRequest
'Usage
Dim instance As GetAddressInfoServiceRequest
```

``` csharp
[DataContractAttribute]
public abstract class GetAddressInfoServiceRequest : ServiceRequest
```

``` c++
[DataContractAttribute]
public ref class GetAddressInfoServiceRequest abstract : public ServiceRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceRequest  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressFormattingServiceRequest](getaddressformattingservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCitiesServiceRequest](getcitiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountiesServiceRequest](getcountiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountryRegionsServiceRequest](getcountryregionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDistrictServiceRequest](getdistrictservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFromZipPostalCodeServiceRequest](getfromzippostalcodeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStateProvincesServiceRequest](getstateprovincesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetZipCodesServiceRequest](getzipcodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

