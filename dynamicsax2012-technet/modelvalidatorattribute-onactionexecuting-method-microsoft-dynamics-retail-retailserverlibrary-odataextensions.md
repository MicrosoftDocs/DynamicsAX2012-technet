---
title: ModelValidatorAttribute.OnActionExecuting Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: OnActionExecuting Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.ModelValidatorAttribute.OnActionExecuting(System.Web.Http.Controllers.HttpActionContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.modelvalidatorattribute.onactionexecuting(v=AX.60)
ms:contentKeyID: 62202526
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.ModelValidatorAttribute.OnActionExecuting
dev_langs:
- CSharp
- C++
- VB
---

# OnActionExecuting Method

The action executing event handler.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub OnActionExecuting ( _
    actionContext As HttpActionContext _
)
'Usage
Dim instance As ModelValidatorAttribute
Dim actionContext As HttpActionContext

instance.OnActionExecuting(actionContext)
```

``` csharp
public override void OnActionExecuting(
    HttpActionContext actionContext
)
```

``` c++
public:
virtual void OnActionExecuting(
    HttpActionContext^ actionContext
) override
```

#### Parameters

  - actionContext  
    Type: HttpActionContext  

## See Also

#### Reference

[ModelValidatorAttribute Class](modelvalidatorattribute-class-microsoft-dynamics-retail-retailserverlibrary-odataextensions.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

