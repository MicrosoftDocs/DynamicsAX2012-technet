---
title: ResponseError.ErrorCode Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ErrorCode Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.ErrorCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.responseerror.errorcode(v=AX.60)
ms:contentKeyID: 62204319
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.ErrorCode
dev_langs:
- CSharp
- C++
- VB
---

# ErrorCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the error code.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ErrorCode As String
    Get
    Set
'Usage
Dim instance As ResponseError
Dim value As String

value = instance.ErrorCode

instance.ErrorCode = value
```

``` csharp
[DataMemberAttribute]
public string ErrorCode { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ErrorCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ResponseError Class](responseerror-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

