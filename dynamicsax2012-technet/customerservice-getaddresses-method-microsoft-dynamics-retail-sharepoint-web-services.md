---
title: CustomerService.GetAddresses Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.GetAddresses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.customerservice.getaddresses(v=AX.60)
ms:contentKeyID: 62203253
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.GetAddresses
dev_langs:
- CSharp
- C++
- VB
---

# GetAddresses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the addresses.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetAddresses As AddressCollectionResponse
'Usage
Dim instance As CustomerService
Dim returnValue As AddressCollectionResponse

returnValue = instance.GetAddresses()
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public AddressCollectionResponse GetAddresses()
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual AddressCollectionResponse^ GetAddresses() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.AddressCollectionResponse](addresscollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
An address collection response.  

#### Implements

[ICustomerService.GetAddresses()](icustomerservice-getaddresses-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CustomerService Class](customerservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

