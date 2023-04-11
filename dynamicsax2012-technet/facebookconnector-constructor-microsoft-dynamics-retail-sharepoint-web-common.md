---
title: FacebookConnector Constructor  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: FacebookConnector Constructor
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookConnector.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.facebookconnector.facebookconnector(v=AX.60)
ms:contentKeyID: 62203549
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookConnector.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# FacebookConnector Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [FacebookConnector](facebookconnector-class-microsoft-dynamics-retail-sharepoint-web-common.md) class.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    applicationId As String, _
    applicationSecret As String _
)
'Usage
Dim applicationId As String
Dim applicationSecret As String

Dim instance As New FacebookConnector(applicationId, _
    applicationSecret)
```

``` csharp
public FacebookConnector(
    string applicationId,
    string applicationSecret
)
```

``` c++
public:
FacebookConnector(
    String^ applicationId, 
    String^ applicationSecret
)
```

#### Parameters

  - applicationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - applicationSecret  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[FacebookConnector Class](facebookconnector-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

