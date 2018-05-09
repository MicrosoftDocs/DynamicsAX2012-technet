---
title: GetReceiptRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetReceiptRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getreceiptrequesthandler(v=AX.60)
ms:contentKeyID: 62204582
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptRequestHandler Class

The request handler for GetReceiptRequest class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetReceiptRequestHandler _
    Inherits WorkflowRequestHandler(Of GetReceiptRequest, GetReceiptResponse)
'Usage
Dim instance As GetReceiptRequestHandler
```

``` csharp
public sealed class GetReceiptRequestHandler : WorkflowRequestHandler<GetReceiptRequest, GetReceiptResponse>
```

``` c++
public ref class GetReceiptRequestHandler sealed : public WorkflowRequestHandler<GetReceiptRequest^, GetReceiptResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetReceiptRequest](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetReceiptResponse](getreceiptresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

