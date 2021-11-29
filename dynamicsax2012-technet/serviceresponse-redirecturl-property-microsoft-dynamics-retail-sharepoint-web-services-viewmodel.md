---
title: ServiceResponse.RedirectUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: RedirectUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ServiceResponse.RedirectUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.serviceresponse.redirecturl(v=AX.60)
ms:contentKeyID: 62203276
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ServiceResponse.RedirectUrl
dev_langs:
- CSharp
- C++
- VB
---

# RedirectUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the has error redirect url.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RedirectUrl As String
    Get
    Set
'Usage
Dim instance As ServiceResponse
Dim value As String

value = instance.RedirectUrl

instance.RedirectUrl = value
```

``` csharp
[DataMemberAttribute]
public string RedirectUrl { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ RedirectUrl {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

