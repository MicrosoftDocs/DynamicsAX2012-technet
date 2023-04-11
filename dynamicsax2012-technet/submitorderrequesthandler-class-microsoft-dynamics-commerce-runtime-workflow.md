---
title: SubmitOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SubmitOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.submitorderrequesthandler(v=AX.60)
ms:contentKeyID: 49855604
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SubmitOrderRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for the submit order request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SubmitOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of CreateOrderFromCartRequest, CreateOrderFromCartResponse)
'Usage
Dim instance As SubmitOrderRequestHandler
```

``` csharp
public sealed class SubmitOrderRequestHandler : WorkflowRequestHandler<CreateOrderFromCartRequest, CreateOrderFromCartResponse>
```

``` c++
public ref class SubmitOrderRequestHandler sealed : public WorkflowRequestHandler<CreateOrderFromCartRequest^, CreateOrderFromCartResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[CreateOrderFromCartRequest](createorderfromcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [CreateOrderFromCartResponse](createorderfromcartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

