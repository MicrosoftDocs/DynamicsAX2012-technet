---
title: AuthenticationModule.ApplicationPostAuthenticateRequest Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: ApplicationPostAuthenticateRequest Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.AuthenticationModule.ApplicationPostAuthenticateRequest(System.Object,System.EventArgs)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.authenticationmodule.applicationpostauthenticaterequest(v=AX.60)
ms:contentKeyID: 62201856
author: tfehr
ms.author: daxcpft
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.AuthenticationModule.ApplicationPostAuthenticateRequest
dev_langs:
- CSharp
- C++
- VB
---

# ApplicationPostAuthenticateRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Occurs when a security module has established the identity of the user and performs post authentication routine. Validates identity, and, if successful, writes the security token to the session cookie.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Sub ApplicationPostAuthenticateRequest ( _
    sender As Object, _
    e As EventArgs _
)
'Usage
Dim instance As AuthenticationModule
Dim sender As Object
Dim e As EventArgs

instance.ApplicationPostAuthenticateRequest(sender, _
    e)
```

``` csharp
public void ApplicationPostAuthenticateRequest(
    Object sender,
    EventArgs e
)
```

``` c++
public:
void ApplicationPostAuthenticateRequest(
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

[AuthenticationModule Class](authenticationmodule-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

