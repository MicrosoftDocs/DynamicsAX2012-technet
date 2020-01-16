---
title: CancelOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CancelOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.CancelOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cancelorderrequesthandler(v=AX.60)
ms:contentKeyID: 62208059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CancelOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# CancelOrderRequestHandler Class

Pick up at store request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CancelOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of CancelOrderRequest, CancelOrderResponse)
'Usage
Dim instance As CancelOrderRequestHandler
```

``` csharp
public sealed class CancelOrderRequestHandler : WorkflowRequestHandler<CancelOrderRequest, CancelOrderResponse>
```

``` c++
public ref class CancelOrderRequestHandler sealed : public WorkflowRequestHandler<CancelOrderRequest^, CancelOrderResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[CancelOrderRequest](cancelorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [CancelOrderResponse](cancelorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.CancelOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

