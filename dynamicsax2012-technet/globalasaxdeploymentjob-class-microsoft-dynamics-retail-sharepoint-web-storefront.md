---
title: GlobalASAXDeploymentJob Class (Microsoft.Dynamics.Retail.SharePoint.Web.Storefront)
TOCTitle: GlobalASAXDeploymentJob Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.GlobalASAXDeploymentJob
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.storefront.globalasaxdeploymentjob(v=AX.60)
ms:contentKeyID: 62206176
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.GlobalASAXDeploymentJob
dev_langs:
- CSharp
- C++
- VB
---

# GlobalASAXDeploymentJob Class

Job that installs the global.asax file in the web app. Note: There is no corresponding job that removes this file, as we really do not know if other features rely on this file and we do not want to remove stuff that is not ours.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Storefront](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Class GlobalASAXDeploymentJob _
    Inherits SPJobDefinition
'Usage
Dim instance As GlobalASAXDeploymentJob
```

``` csharp
public class GlobalASAXDeploymentJob : SPJobDefinition
```

``` c++
public ref class GlobalASAXDeploymentJob : public SPJobDefinition
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPAutoSerializingObject  
    SPPersistedObject  
      SPJobDefinition  
        Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.GlobalASAXDeploymentJob  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Storefront Namespace](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)

