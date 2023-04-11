---
title: CommerceRuntimeExceptionFilterAttribute.OnException Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: OnException Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceRuntimeExceptionFilterAttribute.OnException(System.Web.Http.Filters.HttpActionExecutedContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.commerceruntimeexceptionfilterattribute.onexception(v=AX.60)
ms:contentKeyID: 62202032
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceRuntimeExceptionFilterAttribute.OnException
dev_langs:
- CSharp
- C++
- VB
---

# OnException Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The CommerceRuntime exception handler.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub OnException ( _
    actionExecutedContext As HttpActionExecutedContext _
)
'Usage
Dim instance As CommerceRuntimeExceptionFilterAttribute
Dim actionExecutedContext As HttpActionExecutedContext

instance.OnException(actionExecutedContext)
```

``` csharp
public override void OnException(
    HttpActionExecutedContext actionExecutedContext
)
```

``` c++
public:
virtual void OnException(
    HttpActionExecutedContext^ actionExecutedContext
) override
```

#### Parameters

  - actionExecutedContext  
    Type: HttpActionExecutedContext  

## See Also

#### Reference

[CommerceRuntimeExceptionFilterAttribute Class](commerceruntimeexceptionfilterattribute-class-microsoft-dynamics-retail-retailserverlibrary-odataextensions.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

