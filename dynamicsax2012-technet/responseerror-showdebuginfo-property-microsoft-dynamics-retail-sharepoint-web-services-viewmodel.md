---
title: ResponseError.ShowDebugInfo Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShowDebugInfo Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.ShowDebugInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.responseerror.showdebuginfo(v=AX.60)
ms:contentKeyID: 62207356
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.ShowDebugInfo
dev_langs:
- CSharp
- C++
- VB
---

# ShowDebugInfo Property

Gets or sets the value to indicate to client whether to show additional technical detail in error.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShowDebugInfo As Boolean
    Get
    Set
'Usage
Dim instance As ResponseError
Dim value As Boolean

value = instance.ShowDebugInfo

instance.ShowDebugInfo = value
```

``` csharp
[DataMemberAttribute]
public bool ShowDebugInfo { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool ShowDebugInfo {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ResponseError Class](responseerror-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

