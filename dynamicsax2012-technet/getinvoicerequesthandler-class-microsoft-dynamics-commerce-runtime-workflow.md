---
title: GetInvoiceRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetInvoiceRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetInvoiceRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getinvoicerequesthandler(v=AX.60)
ms:contentKeyID: 62208280
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetInvoiceRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetInvoiceRequestHandler Class

Handles workflow for recall customer order into a cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetInvoiceRequestHandler _
    Inherits WorkflowRequestHandler(Of GetInvoiceRequest, GetInvoiceResponse)
'Usage
Dim instance As GetInvoiceRequestHandler
```

``` csharp
public sealed class GetInvoiceRequestHandler : WorkflowRequestHandler<GetInvoiceRequest, GetInvoiceResponse>
```

``` c++
public ref class GetInvoiceRequestHandler sealed : public WorkflowRequestHandler<GetInvoiceRequest^, GetInvoiceResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetInvoiceRequest](getinvoicerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetInvoiceResponse](getinvoiceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetInvoiceRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

