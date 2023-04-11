---
title: GlobalASAXDeploymentJob.Execute Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Storefront)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.GlobalASAXDeploymentJob.Execute(System.Guid)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.storefront.globalasaxdeploymentjob.execute(v=AX.60)
ms:contentKeyID: 62202562
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.GlobalASAXDeploymentJob.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the job definition on the local machine and is intended to be used only by the timer service.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Storefront](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub Execute ( _
    targetInstanceId As Guid _
)
'Usage
Dim instance As GlobalASAXDeploymentJob
Dim targetInstanceId As Guid

instance.Execute(targetInstanceId)
```

``` csharp
public override void Execute(
    Guid targetInstanceId
)
```

``` c++
public:
virtual void Execute(
    Guid targetInstanceId
) override
```

#### Parameters

  - targetInstanceId  
    Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  

## See Also

#### Reference

[GlobalASAXDeploymentJob Class](globalasaxdeploymentjob-class-microsoft-dynamics-retail-sharepoint-web-storefront.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Storefront Namespace](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)

