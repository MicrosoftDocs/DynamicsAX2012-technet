---
title: AuthenticationModule Class (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: AuthenticationModule Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.AuthenticationModule
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.authenticationmodule(v=AX.60)
ms:contentKeyID: 62203084
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.AuthenticationModule
dev_langs:
- CSharp
- C++
- VB
---

# AuthenticationModule Class

Specifies the authentication module that verifies the request's [IPrincipal](https://technet.microsoft.com/library/f8kt7fb8\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Class AuthenticationModule _
    Implements IHttpModule
'Usage
Dim instance As AuthenticationModule
```

``` csharp
public class AuthenticationModule : IHttpModule
```

``` c++
public ref class AuthenticationModule : IHttpModule
```

## Remarks

Thread.CurrentPrincipal has been assigned when this filter gets called. Based on that, a new commerce principal will be constructed and assigned to Thread.CurrentPrincipal.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Retail.RetailServerLibrary.AuthenticationModule  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

