---
title: CommerceAuthorizationAttribute.IsAuthorized Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: IsAuthorized Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.IsAuthorized(System.Web.Http.Controllers.HttpActionContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.commerceauthorizationattribute.isauthorized(v=AX.60)
ms:contentKeyID: 62202001
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.IsAuthorized
dev_langs:
- CSharp
- C++
- VB
---

# IsAuthorized Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks authorization for all OData calls.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function IsAuthorized ( _
    actionContext As HttpActionContext _
) As Boolean
'Usage
Dim actionContext As HttpActionContext
Dim returnValue As Boolean

returnValue = Me.IsAuthorized(actionContext)
```

``` csharp
protected override bool IsAuthorized(
    HttpActionContext actionContext
)
```

``` c++
protected:
virtual bool IsAuthorized(
    HttpActionContext^ actionContext
) override
```

#### Parameters

  - actionContext  
    Type: HttpActionContext  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) result of authorization.  

## See Also

#### Reference

[CommerceAuthorizationAttribute Class](commerceauthorizationattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

