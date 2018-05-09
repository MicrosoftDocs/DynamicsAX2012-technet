---
title: PipelineRequestHandler.OnAuthorizeRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition)
TOCTitle: OnAuthorizeRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.OnAuthorizeRequest(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.composition.pipelinerequesthandler.onauthorizerequest(v=AX.60)
ms:contentKeyID: 49844967
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.OnAuthorizeRequest
dev_langs:
- CSharp
- C++
- VB
---

# OnAuthorizeRequest Method

Invoked to authorize the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub OnAuthorizeRequest ( _
    context As RequestContext _
)
'Usage
Dim context As RequestContext

Me.OnAuthorizeRequest(context)
```

``` csharp
protected virtual void OnAuthorizeRequest(
    RequestContext context
)
```

``` c++
protected:
virtual void OnAuthorizeRequest(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[PipelineRequestHandler Class](pipelinerequesthandler-class-microsoft-dynamics-commerce-runtime-workflow-composition.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition Namespace](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)

