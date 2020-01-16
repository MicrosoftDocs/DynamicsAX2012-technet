---
title: ResponseError.ExtendedErrorMessage Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ExtendedErrorMessage Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.ExtendedErrorMessage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.responseerror.extendederrormessage(v=AX.60)
ms:contentKeyID: 62207165
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.ExtendedErrorMessage
dev_langs:
- CSharp
- C++
- VB
---

# ExtendedErrorMessage Property

Gets or sets the value of the error message as provided by the back-end.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExtendedErrorMessage As String
    Get
    Set
'Usage
Dim instance As ResponseError
Dim value As String

value = instance.ExtendedErrorMessage

instance.ExtendedErrorMessage = value
```

``` csharp
[DataMemberAttribute]
public string ExtendedErrorMessage { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ExtendedErrorMessage {
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

