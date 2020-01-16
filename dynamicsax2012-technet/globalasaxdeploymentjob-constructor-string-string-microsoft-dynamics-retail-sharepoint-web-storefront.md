---
title: GlobalASAXDeploymentJob Constructor (String, , String) (Microsoft.Dynamics.Retail.SharePoint.Web.Storefront)
TOCTitle: GlobalASAXDeploymentJob Constructor (String, , String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.GlobalASAXDeploymentJob.#ctor(System.String,Microsoft.SharePoint.Administration.SPWebApplication,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.storefront.globalasaxdeploymentjob.globalasaxdeploymentjob(v=AX.60)
ms:contentKeyID: 62206246
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GlobalASAXDeploymentJob Constructor (String, , String)

Initializes a new instance of the GlobalAsaxDeploymentJob class and provides parameters for specifying key objects.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Storefront](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    jobName As String, _
    webApplication As SPWebApplication, _
    globalASAXSourceFileRelativePath As String _
)
'Usage
Dim jobName As String
Dim webApplication As SPWebApplication
Dim globalASAXSourceFileRelativePath As String

Dim instance As New GlobalASAXDeploymentJob(jobName, _
    webApplication, globalASAXSourceFileRelativePath)
```

``` csharp
public GlobalASAXDeploymentJob(
    string jobName,
    SPWebApplication webApplication,
    string globalASAXSourceFileRelativePath
)
```

``` c++
public:
GlobalASAXDeploymentJob(
    String^ jobName, 
    SPWebApplication^ webApplication, 
    String^ globalASAXSourceFileRelativePath
)
```

#### Parameters

  - jobName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - webApplication  
    Type: SPWebApplication  

<!-- end list -->

  - globalASAXSourceFileRelativePath  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## Remarks

This overload

## See Also

#### Reference

[GlobalASAXDeploymentJob Class](globalasaxdeploymentjob-class-microsoft-dynamics-retail-sharepoint-web-storefront.md)

[GlobalASAXDeploymentJob Overload](globalasaxdeploymentjob-constructor-microsoft-dynamics-retail-sharepoint-web-storefront.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Storefront Namespace](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)

