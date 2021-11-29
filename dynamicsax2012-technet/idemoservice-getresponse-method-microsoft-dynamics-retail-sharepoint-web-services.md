---
title: IDemoService.GetResponse Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetResponse Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IDemoService.GetResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.idemoservice.getresponse(v=AX.60)
ms:contentKeyID: 62206832
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IDemoService.GetResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetResponse Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a service response.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetResponse As DemoServiceResponse
'Usage
Dim instance As IDemoService
Dim returnValue As DemoServiceResponse

returnValue = instance.GetResponse()
```

``` csharp
[OperationContractAttribute]
DemoServiceResponse GetResponse()
```

``` c++
[OperationContractAttribute]
DemoServiceResponse^ GetResponse()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DemoServiceResponse](demoserviceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The response from the demo service.  

## See Also

#### Reference

[IDemoService Interface](idemoservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

