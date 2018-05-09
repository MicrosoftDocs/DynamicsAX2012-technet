---
title: RecalculateOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: RecalculateOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.RecalculateOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.recalculateorderrequesthandler(v=AX.60)
ms:contentKeyID: 62208258
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.RecalculateOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# RecalculateOrderRequestHandler Class

Handles workflow for order recalculation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class RecalculateOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of RecalculateOrderRequest, RecalculateOrderResponse)
'Usage
Dim instance As RecalculateOrderRequestHandler
```

``` csharp
public sealed class RecalculateOrderRequestHandler : WorkflowRequestHandler<RecalculateOrderRequest, RecalculateOrderResponse>
```

``` c++
public ref class RecalculateOrderRequestHandler sealed : public WorkflowRequestHandler<RecalculateOrderRequest^, RecalculateOrderResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[RecalculateOrderRequest](recalculateorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [RecalculateOrderResponse](recalculateorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.RecalculateOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

