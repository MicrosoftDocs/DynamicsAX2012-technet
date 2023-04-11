---
title: GetPurchaseOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetPurchaseOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPurchaseOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getpurchaseorderrequesthandler(v=AX.60)
ms:contentKeyID: 62211809
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPurchaseOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetPurchaseOrderRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The class to handle GetPurchaseOrderRequest.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetPurchaseOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of GetPurchaseOrderRequest, GetPurchaseOrderResponse)
'Usage
Dim instance As GetPurchaseOrderRequestHandler
```

``` csharp
public sealed class GetPurchaseOrderRequestHandler : WorkflowRequestHandler<GetPurchaseOrderRequest, GetPurchaseOrderResponse>
```

``` c++
public ref class GetPurchaseOrderRequestHandler sealed : public WorkflowRequestHandler<GetPurchaseOrderRequest^, GetPurchaseOrderResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetPurchaseOrderRequest](getpurchaseorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetPurchaseOrderResponse](getpurchaseorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPurchaseOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

