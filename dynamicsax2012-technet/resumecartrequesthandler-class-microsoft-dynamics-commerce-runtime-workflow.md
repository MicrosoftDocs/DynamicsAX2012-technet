---
title: ResumeCartRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ResumeCartRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeCartRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.resumecartrequesthandler(v=AX.60)
ms:contentKeyID: 62212636
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeCartRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# ResumeCartRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles workflow to resume suspended cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ResumeCartRequestHandler _
    Inherits WorkflowRequestHandler(Of ResumeCartRequest, ResumeCartResponse)
'Usage
Dim instance As ResumeCartRequestHandler
```

``` csharp
public sealed class ResumeCartRequestHandler : WorkflowRequestHandler<ResumeCartRequest, ResumeCartResponse>
```

``` c++
public ref class ResumeCartRequestHandler sealed : public WorkflowRequestHandler<ResumeCartRequest^, ResumeCartResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[ResumeCartRequest](resumecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [ResumeCartResponse](resumecartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeCartRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

