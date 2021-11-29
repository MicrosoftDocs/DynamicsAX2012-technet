---
title: GetTransferOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetTransferOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetTransferOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.gettransferorderrequesthandler(v=AX.60)
ms:contentKeyID: 62206229
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetTransferOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetTransferOrderRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The class to handle GetTransferOrderRequest.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetTransferOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of GetTransferOrderRequest, GetTransferOrderResponse)
'Usage
Dim instance As GetTransferOrderRequestHandler
```

``` csharp
public sealed class GetTransferOrderRequestHandler : WorkflowRequestHandler<GetTransferOrderRequest, GetTransferOrderResponse>
```

``` c++
public ref class GetTransferOrderRequestHandler sealed : public WorkflowRequestHandler<GetTransferOrderRequest^, GetTransferOrderResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetTransferOrderRequest](gettransferorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetTransferOrderResponse](gettransferorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetTransferOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

