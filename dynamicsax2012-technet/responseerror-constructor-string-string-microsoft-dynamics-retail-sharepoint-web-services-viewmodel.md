---
title: ResponseError Constructor (String, String) (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ResponseError Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ResponseError.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.responseerror.responseerror(v=AX.60)
ms:contentKeyID: 62202388
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ResponseError Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates the instance of the [ResponseError](responseerror-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorCode As String, _
    errorMessage As String _
)
'Usage
Dim errorCode As String
Dim errorMessage As String

Dim instance As New ResponseError(errorCode, _
    errorMessage)
```

``` csharp
public ResponseError(
    string errorCode,
    string errorMessage
)
```

``` c++
public:
ResponseError(
    String^ errorCode, 
    String^ errorMessage
)
```

#### Parameters

  - errorCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - errorMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ResponseError Class](responseerror-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[ResponseError Overload](responseerror-constructor-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

