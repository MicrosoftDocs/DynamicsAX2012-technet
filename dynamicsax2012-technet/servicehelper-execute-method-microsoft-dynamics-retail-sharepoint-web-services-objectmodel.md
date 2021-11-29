---
title: ServiceHelper.Execute Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ServiceHelper.Execute(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ServiceResponse,Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ServiceExecutionHandler)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.servicehelper.execute(v=AX.60)
ms:contentKeyID: 62202068
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ServiceHelper.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes handler and handles exceptions.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub Execute ( _
    response As ServiceResponse, _
    executionHandler As ServiceExecutionHandler _
)
'Usage
Dim response As ServiceResponse
Dim executionHandler As ServiceExecutionHandler

ServiceHelper.Execute(response, executionHandler)
```

``` csharp
public static void Execute(
    ServiceResponse response,
    ServiceExecutionHandler executionHandler
)
```

``` c++
public:
static void Execute(
    ServiceResponse^ response, 
    ServiceExecutionHandler^ executionHandler
)
```

#### Parameters

  - response  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

<!-- end list -->

  - executionHandler  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ServiceExecutionHandler](serviceexecutionhandler-delegate-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)  

## See Also

#### Reference

[ServiceHelper Class](servicehelper-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

