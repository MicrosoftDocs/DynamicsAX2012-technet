---
title: CommerceAuthorizationAttribute.HandleUnauthorizedRequest Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: HandleUnauthorizedRequest Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.HandleUnauthorizedRequest(System.Web.Http.Controllers.HttpActionContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.commerceauthorizationattribute.handleunauthorizedrequest(v=AX.60)
ms:contentKeyID: 62203085
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.HandleUnauthorizedRequest
dev_langs:
- CSharp
- C++
- VB
---

# HandleUnauthorizedRequest Method

Handles all unauthorized errors to return proper HttpCode to client.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub HandleUnauthorizedRequest ( _
    actionContext As HttpActionContext _
)
'Usage
Dim actionContext As HttpActionContext

Me.HandleUnauthorizedRequest(actionContext)
```

``` csharp
protected override void HandleUnauthorizedRequest(
    HttpActionContext actionContext
)
```

``` c++
protected:
virtual void HandleUnauthorizedRequest(
    HttpActionContext^ actionContext
) override
```

#### Parameters

  - actionContext  
    Type: HttpActionContext  

## See Also

#### Reference

[CommerceAuthorizationAttribute Class](commerceauthorizationattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

