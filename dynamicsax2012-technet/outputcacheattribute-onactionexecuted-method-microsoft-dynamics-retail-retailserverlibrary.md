---
title: OutputCacheAttribute.OnActionExecuted Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: OnActionExecuted Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.OutputCacheAttribute.OnActionExecuted(System.Web.Http.Filters.HttpActionExecutedContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.outputcacheattribute.onactionexecuted(v=AX.60)
ms:contentKeyID: 62203729
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.OutputCacheAttribute.OnActionExecuted
dev_langs:
- CSharp
- C++
- VB
---

# OnActionExecuted Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prepares the response cache headers.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub OnActionExecuted ( _
    actionExecutedContext As HttpActionExecutedContext _
)
'Usage
Dim instance As OutputCacheAttribute
Dim actionExecutedContext As HttpActionExecutedContext

instance.OnActionExecuted(actionExecutedContext)
```

``` csharp
public override void OnActionExecuted(
    HttpActionExecutedContext actionExecutedContext
)
```

``` c++
public:
virtual void OnActionExecuted(
    HttpActionExecutedContext^ actionExecutedContext
) override
```

#### Parameters

  - actionExecutedContext  
    Type: HttpActionExecutedContext  

## See Also

#### Reference

[OutputCacheAttribute Class](outputcacheattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

