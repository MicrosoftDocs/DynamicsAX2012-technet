---
title: PipelineRequestHandler.OnBeginRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition)
TOCTitle: OnBeginRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.OnBeginRequest(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.composition.pipelinerequesthandler.onbeginrequest(v=AX.60)
ms:contentKeyID: 49823080
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.OnBeginRequest
dev_langs:
- CSharp
- C++
- VB
---

# OnBeginRequest Method

Invoked when a request is submitted to the handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub OnBeginRequest ( _
    context As RequestContext _
)
'Usage
Dim context As RequestContext

Me.OnBeginRequest(context)
```

``` csharp
protected virtual void OnBeginRequest(
    RequestContext context
)
```

``` c++
protected:
virtual void OnBeginRequest(
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

