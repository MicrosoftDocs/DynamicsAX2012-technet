---
title: ResponseError.StackTrace Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: StackTrace Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.StackTrace
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.responseerror.stacktrace(v=AX.60)
ms:contentKeyID: 62202963
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.StackTrace
dev_langs:
- CSharp
- C++
- VB
---

# StackTrace Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the stack trace of the error.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StackTrace As String
    Get
    Set
'Usage
Dim instance As ResponseError
Dim value As String

value = instance.StackTrace

instance.StackTrace = value
```

``` csharp
[DataMemberAttribute]
public string StackTrace { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StackTrace {
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

