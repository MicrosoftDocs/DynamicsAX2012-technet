---
title: SuspendCartRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SuspendCartRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SuspendCartRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.suspendcartrequesthandler(v=AX.60)
ms:contentKeyID: 62209884
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SuspendCartRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SuspendCartRequestHandler Class

Handles workflow to suspend cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SuspendCartRequestHandler _
    Inherits WorkflowRequestHandler(Of SuspendCartRequest, SuspendCartResponse)
'Usage
Dim instance As SuspendCartRequestHandler
```

``` csharp
public sealed class SuspendCartRequestHandler : WorkflowRequestHandler<SuspendCartRequest, SuspendCartResponse>
```

``` c++
public ref class SuspendCartRequestHandler sealed : public WorkflowRequestHandler<SuspendCartRequest^, SuspendCartResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SuspendCartRequest](suspendcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SuspendCartResponse](suspendcartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SuspendCartRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

