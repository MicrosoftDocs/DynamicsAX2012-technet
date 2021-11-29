---
title: PipelineRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition)
TOCTitle: PipelineRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.composition.pipelinerequesthandler(v=AX.60)
ms:contentKeyID: 49830749
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# PipelineRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The request handler that initiates the request pipeline.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class PipelineRequestHandler _
    Implements IRequestPipeline
'Usage
Dim instance As PipelineRequestHandler
```

``` csharp
public class PipelineRequestHandler : IRequestPipeline
```

``` c++
public ref class PipelineRequestHandler : IRequestPipeline
```

## Remarks

Initial implementation of the pipeline assuming that this does not vary much per request. If it does, we may need to make each of the steps as individual handlers.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition.PipelineRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow.Composition Namespace](microsoft-dynamics-commerce-runtime-workflow-composition-namespace.md)

