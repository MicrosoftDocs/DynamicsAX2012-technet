---
title: Register.RegisterUser_CreatingUser Method  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: RegisterUser_CreatingUser Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Register.RegisterUser_CreatingUser(System.Object,System.Web.UI.WebControls.LoginCancelEventArgs)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.register.registeruser_creatinguser(v=AX.60)
ms:contentKeyID: 62206392
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Register.RegisterUser_CreatingUser
dev_langs:
- CSharp
- C++
- VB
---

# RegisterUser\_CreatingUser Method

Event raised before a new user has been created.

Before we add the identity try to associate the email to the customer using the supplied loyalty card number.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Protected Sub RegisterUser_CreatingUser ( _
    sender As Object, _
    e As LoginCancelEventArgs _
)
'Usage
Dim sender As Object
Dim e As LoginCancelEventArgs

Me.RegisterUser_CreatingUser(sender, _
    e)
```

``` csharp
protected void RegisterUser_CreatingUser(
    Object sender,
    LoginCancelEventArgs e
)
```

``` c++
protected:
void RegisterUser_CreatingUser(
    Object^ sender, 
    LoginCancelEventArgs^ e
)
```

#### Parameters

  - sender  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - e  
    Type: [System.Web.UI.WebControls.LoginCancelEventArgs](https://technet.microsoft.com/library/b9fyfx4w\(v=ax.60\))  

## See Also

#### Reference

[Register Class](register-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

