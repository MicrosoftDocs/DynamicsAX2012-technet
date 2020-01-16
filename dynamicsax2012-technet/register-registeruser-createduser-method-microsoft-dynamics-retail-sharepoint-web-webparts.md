---
title: Register.RegisterUser_CreatedUser Method  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: RegisterUser_CreatedUser Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Register.RegisterUser_CreatedUser(System.Object,System.EventArgs)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.register.registeruser_createduser(v=AX.60)
ms:contentKeyID: 62203323
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Register.RegisterUser_CreatedUser
dev_langs:
- CSharp
- C++
- VB
---

# RegisterUser\_CreatedUser Method

Event raised after a new user has been created.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Protected Sub RegisterUser_CreatedUser ( _
    sender As Object, _
    e As EventArgs _
)
'Usage
Dim sender As Object
Dim e As EventArgs

Me.RegisterUser_CreatedUser(sender, _
    e)
```

``` csharp
protected void RegisterUser_CreatedUser(
    Object sender,
    EventArgs e
)
```

``` c++
protected:
void RegisterUser_CreatedUser(
    Object^ sender, 
    EventArgs^ e
)
```

#### Parameters

  - sender  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - e  
    Type: [System.EventArgs](https://technet.microsoft.com/library/118wxtk3\(v=ax.60\))  

## See Also

#### Reference

[Register Class](register-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

