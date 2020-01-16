---
title: RecallCustomerOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: RecallCustomerOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.RecallCustomerOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.recallcustomerorderrequesthandler(v=AX.60)
ms:contentKeyID: 62211207
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.RecallCustomerOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# RecallCustomerOrderRequestHandler Class

Handles workflow for recall customer order into a cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class RecallCustomerOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of RecallCustomerOrderRequest, RecallCustomerOrderResponse)
'Usage
Dim instance As RecallCustomerOrderRequestHandler
```

``` csharp
public sealed class RecallCustomerOrderRequestHandler : WorkflowRequestHandler<RecallCustomerOrderRequest, RecallCustomerOrderResponse>
```

``` c++
public ref class RecallCustomerOrderRequestHandler sealed : public WorkflowRequestHandler<RecallCustomerOrderRequest^, RecallCustomerOrderResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[RecallCustomerOrderRequest](recallcustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [RecallCustomerOrderResponse](recallcustomerorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.RecallCustomerOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

