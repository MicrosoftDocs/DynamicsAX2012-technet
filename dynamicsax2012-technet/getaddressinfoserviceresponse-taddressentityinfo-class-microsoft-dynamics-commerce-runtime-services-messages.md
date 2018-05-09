---
title: GetAddressInfoServiceResponse(TAddressEntityInfo) Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetAddressInfoServiceResponse(TAddressEntityInfo) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse`1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn685669(v=AX.60)
ms:contentKeyID: 62211135
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse`1
dev_langs:
- CSharp
- C++
- VB
---

# GetAddressInfoServiceResponse(TAddressEntityInfo) Class

Base class for all address enumeration response objects.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetAddressInfoServiceResponse(Of TAddressEntityInfo As CommerceEntity) _
    Inherits Response
'Usage
Dim instance As GetAddressInfoServiceResponse(Of TAddressEntityInfo)
```

``` csharp
[DataContractAttribute]
public class GetAddressInfoServiceResponse<TAddressEntityInfo> : Response
where TAddressEntityInfo : CommerceEntity
```

``` c++
[DataContractAttribute]
generic<typename TAddressEntityInfo>
where TAddressEntityInfo : CommerceEntity
public ref class GetAddressInfoServiceResponse : public Response
```

#### Type Parameters

  - TAddressEntityInfo

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse\<TAddressEntityInfo\>  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressFormattingServiceResponse](getaddressformattingserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCitiesServiceResponse](getcitiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountiesServiceResponse](getcountiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountryRegionsServiceResponse](getcountryregionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDistrictServiceResponse](getdistrictserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFromZipPostalCodeServiceResponse](getfromzippostalcodeserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStateProvincesServiceResponse](getstateprovincesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetZipCodesServiceResponse](getzipcodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

