---
title: PickAndPackOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: PickAndPackOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.PickAndPackOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.pickandpackorderrequesthandler(v=AX.60)
ms:contentKeyID: 62214225
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.PickAndPackOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# PickAndPackOrderRequestHandler Class

Workflow for picking list and packing slip creation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class PickAndPackOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of PickAndPackOrderRequest, NullResponse)
'Usage
Dim instance As PickAndPackOrderRequestHandler
```

``` csharp
public sealed class PickAndPackOrderRequestHandler : WorkflowRequestHandler<PickAndPackOrderRequest, NullResponse>
```

``` c++
public ref class PickAndPackOrderRequestHandler sealed : public WorkflowRequestHandler<PickAndPackOrderRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[PickAndPackOrderRequest](pickandpackorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.PickAndPackOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

