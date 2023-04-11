---
title: PipelineRequestHandler.OnPreExecuteRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition)
TOCTitle: OnPreExecuteRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.OnPreExecuteRequest(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.composition.pipelinerequesthandler.onpreexecuterequest(v=AX.60)
ms:contentKeyID: 49841990
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.OnPreExecuteRequest
dev_langs:
- CSharp
- C++
- VB
---

# OnPreExecuteRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Invoked before the execute method is called on the handlers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub OnPreExecuteRequest ( _
    context As RequestContext _
)
'Usage
Dim context As RequestContext

Me.OnPreExecuteRequest(context)
```

``` csharp
protected virtual void OnPreExecuteRequest(
    RequestContext context
)
```

``` c++
protected:
virtual void OnPreExecuteRequest(
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

