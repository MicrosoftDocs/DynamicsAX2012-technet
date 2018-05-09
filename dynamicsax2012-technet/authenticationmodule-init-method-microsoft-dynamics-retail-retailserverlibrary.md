---
title: AuthenticationModule.Init Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: Init Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.AuthenticationModule.Init(System.Web.HttpApplication)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.authenticationmodule.init(v=AX.60)
ms:contentKeyID: 62203832
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.AuthenticationModule.Init
dev_langs:
- CSharp
- C++
- VB
---

# Init Method

Initializes Security Manager.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Sub Init ( _
    context As HttpApplication _
)
'Usage
Dim instance As AuthenticationModule
Dim context As HttpApplication

instance.Init(context)
```

``` csharp
public void Init(
    HttpApplication context
)
```

``` c++
public:
virtual void Init(
    HttpApplication^ context
) sealed
```

#### Parameters

  - context  
    Type: [System.Web.HttpApplication](https://technet.microsoft.com/en-us/library/4wt3wttw\(v=ax.60\))  

#### Implements

[IHttpModule.Init(HttpApplication)](https://technet.microsoft.com/en-us/library/4fxtd0dz\(v=ax.60\))  

## See Also

#### Reference

[AuthenticationModule Class](authenticationmodule-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

