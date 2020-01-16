---
title: GetShipmentsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetShipmentsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getshipmentsrequesthandler(v=AX.60)
ms:contentKeyID: 49832997
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentsRequestHandler Class

Handler for reading shipments.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetShipmentsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetShipmentsRequest, GetShipmentsResponse)
'Usage
Dim instance As GetShipmentsRequestHandler
```

``` csharp
public sealed class GetShipmentsRequestHandler : WorkflowRequestHandler<GetShipmentsRequest, GetShipmentsResponse>
```

``` c++
public ref class GetShipmentsRequestHandler sealed : public WorkflowRequestHandler<GetShipmentsRequest^, GetShipmentsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetShipmentsRequest](getshipmentsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetShipmentsResponse](getshipmentsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

