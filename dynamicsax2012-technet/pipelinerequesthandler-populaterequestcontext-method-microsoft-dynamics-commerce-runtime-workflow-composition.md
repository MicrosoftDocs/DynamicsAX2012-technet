---
title: PipelineRequestHandler.PopulateRequestContext Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition)
TOCTitle: PopulateRequestContext Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.PopulateRequestContext(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.composition.pipelinerequesthandler.populaterequestcontext(v=AX.60)
ms:contentKeyID: 65322941
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler.PopulateRequestContext
dev_langs:
- CSharp
- C++
- VB
---

# PopulateRequestContext Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function PopulateRequestContext ( _
    context As RequestContext _
) As RequestContext
'Usage
Dim context As RequestContext
Dim returnValue As RequestContext

returnValue = PipelineRequestHandler.PopulateRequestContext(context)
```

``` csharp
public static RequestContext PopulateRequestContext(
    RequestContext context
)
```

``` c++
public:
static RequestContext^ PopulateRequestContext(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[PipelineRequestHandler Class](pipelinerequesthandler-class-microsoft-dynamics-commerce-runtime-workflow-composition.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition Namespace](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)

