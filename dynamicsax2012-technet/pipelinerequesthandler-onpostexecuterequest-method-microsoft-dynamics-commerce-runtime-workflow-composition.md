---
title: PipelineRequestHandler.OnPostExecuteRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition)
TOCTitle: OnPostExecuteRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.OnPostExecuteRequest(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.composition.pipelinerequesthandler.onpostexecuterequest(v=AX.60)
ms:contentKeyID: 49856259
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.OnPostExecuteRequest
dev_langs:
- CSharp
- C++
- VB
---

# OnPostExecuteRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Invoked after the handler for the request has returned.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub OnPostExecuteRequest ( _
    context As RequestContext _
)
'Usage
Dim context As RequestContext

Me.OnPostExecuteRequest(context)
```

``` csharp
protected virtual void OnPostExecuteRequest(
    RequestContext context
)
```

``` c++
protected:
virtual void OnPostExecuteRequest(
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

