---
title: GlobalASAXDeploymentJob Constructor (String, , , ) (Microsoft.Dynamics.Retail.SharePoint.Web.Storefront)
TOCTitle: GlobalASAXDeploymentJob Constructor (String, , , )
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.GlobalASAXDeploymentJob.#ctor(System.String,Microsoft.SharePoint.Administration.SPService,Microsoft.SharePoint.Administration.SPServer,Microsoft.SharePoint.Administration.SPJobLockType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.storefront.globalasaxdeploymentjob.globalasaxdeploymentjob(v=AX.60)
ms:contentKeyID: 62206217
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GlobalASAXDeploymentJob Constructor (String, , , )


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the GlobalAsaxDeploymentJob class and provides parameters for specifying key objects.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Storefront](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    jobName As String, _
    service As SPService, _
    server As SPServer, _
    targetType As SPJobLockType _
)
'Usage
Dim jobName As String
Dim service As SPService
Dim server As SPServer
Dim targetType As SPJobLockType

Dim instance As New GlobalASAXDeploymentJob(jobName, _
    service, server, targetType)
```

``` csharp
public GlobalASAXDeploymentJob(
    string jobName,
    SPService service,
    SPServer server,
    SPJobLockType targetType
)
```

``` c++
public:
GlobalASAXDeploymentJob(
    String^ jobName, 
    SPService^ service, 
    SPServer^ server, 
    SPJobLockType targetType
)
```

#### Parameters

  - jobName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - service  
    Type: SPService  

<!-- end list -->

  - server  
    Type: SPServer  

<!-- end list -->

  - targetType  
    Type: SPJobLockType  

## See Also

#### Reference

[GlobalASAXDeploymentJob Class](globalasaxdeploymentjob-class-microsoft-dynamics-retail-sharepoint-web-storefront.md)

[GlobalASAXDeploymentJob Overload](globalasaxdeploymentjob-constructor-microsoft-dynamics-retail-sharepoint-web-storefront.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Storefront Namespace](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)

