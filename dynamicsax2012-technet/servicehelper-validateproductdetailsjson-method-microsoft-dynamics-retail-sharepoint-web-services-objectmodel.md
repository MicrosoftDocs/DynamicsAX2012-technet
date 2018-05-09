---
title: ServiceHelper.ValidateProductDetailsJson Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: ValidateProductDetailsJson Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ServiceHelper.ValidateProductDetailsJson(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.servicehelper.validateproductdetailsjson(v=AX.60)
ms:contentKeyID: 62204683
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ServiceHelper.ValidateProductDetailsJson
dev_langs:
- CSharp
- C++
- VB
---

# ValidateProductDetailsJson Method

Runs validation on that the product details JSON blob. If any errors are found, an appropriate exception is thrown.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ValidateProductDetailsJson ( _
    productDetailsJson As String _
)
'Usage
Dim productDetailsJson As String

ServiceHelper.ValidateProductDetailsJson(productDetailsJson)
```

``` csharp
public static void ValidateProductDetailsJson(
    string productDetailsJson
)
```

``` c++
public:
static void ValidateProductDetailsJson(
    String^ productDetailsJson
)
```

#### Parameters

  - productDetailsJson  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ServiceHelper Class](servicehelper-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

