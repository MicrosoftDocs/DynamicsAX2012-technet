---
title: GetOrdersRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetOrdersRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOrdersRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getordersrequesthandler(v=AX.60)
ms:contentKeyID: 49847089
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOrdersRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetOrdersRequestHandler Class

Handles workflow for GetSalesOrders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetOrdersRequestHandler _
    Inherits WorkflowRequestHandler(Of GetOrdersRequest, GetOrdersResponse)
'Usage
Dim instance As GetOrdersRequestHandler
```

``` csharp
public sealed class GetOrdersRequestHandler : WorkflowRequestHandler<GetOrdersRequest, GetOrdersResponse>
```

``` c++
public ref class GetOrdersRequestHandler sealed : public WorkflowRequestHandler<GetOrdersRequest^, GetOrdersResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetOrdersRequest](getordersrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetOrdersResponse](getordersresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOrdersRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

