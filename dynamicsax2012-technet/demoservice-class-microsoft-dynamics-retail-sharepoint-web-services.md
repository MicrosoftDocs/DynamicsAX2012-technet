---
title: DemoService Class (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: DemoService Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.DemoService
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.demoservice(v=AX.60)
ms:contentKeyID: 62207504
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.DemoService
dev_langs:
- CSharp
- C++
- VB
---

# DemoService Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Service for demo purposes only.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<BasicHttpBindingServiceMetadataExchangeEndpointAttribute> _
<AspNetCompatibilityRequirementsAttribute(RequirementsMode := AspNetCompatibilityRequirementsMode.Required)> _
Public Class DemoService _
    Implements IDemoService
'Usage
Dim instance As DemoService
```

``` csharp
[BasicHttpBindingServiceMetadataExchangeEndpointAttribute]
[AspNetCompatibilityRequirementsAttribute(RequirementsMode = AspNetCompatibilityRequirementsMode.Required)]
public class DemoService : IDemoService
```

``` c++
[BasicHttpBindingServiceMetadataExchangeEndpointAttribute]
[AspNetCompatibilityRequirementsAttribute(RequirementsMode = AspNetCompatibilityRequirementsMode::Required)]
public ref class DemoService : IDemoService
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Retail.SharePoint.Web.Services.DemoService  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

