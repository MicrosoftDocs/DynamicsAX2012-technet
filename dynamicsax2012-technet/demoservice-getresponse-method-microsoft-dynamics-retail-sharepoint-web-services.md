---
title: DemoService.GetResponse Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetResponse Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.DemoService.GetResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.demoservice.getresponse(v=AX.60)
ms:contentKeyID: 62205482
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.DemoService.GetResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetResponse Method

Gets a service response.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetResponse As DemoServiceResponse
'Usage
Dim instance As DemoService
Dim returnValue As DemoServiceResponse

returnValue = instance.GetResponse()
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public DemoServiceResponse GetResponse()
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual DemoServiceResponse^ GetResponse() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DemoServiceResponse](demoserviceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Demo service response.  

#### Implements

[IDemoService.GetResponse()](idemoservice-getresponse-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[DemoService Class](demoservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

