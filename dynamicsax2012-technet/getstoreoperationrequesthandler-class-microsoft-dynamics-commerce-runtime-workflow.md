---
title: GetStoreOperationRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetStoreOperationRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoreOperationRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getstoreoperationrequesthandler(v=AX.60)
ms:contentKeyID: 62210533
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoreOperationRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetStoreOperationRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Save all incoming non-sale transaction from store operations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetStoreOperationRequestHandler _
    Inherits WorkflowRequestHandler(Of GetStoreOperationRequest, GetStoreOperationResponse)
'Usage
Dim instance As GetStoreOperationRequestHandler
```

``` csharp
public class GetStoreOperationRequestHandler : WorkflowRequestHandler<GetStoreOperationRequest, GetStoreOperationResponse>
```

``` c++
public ref class GetStoreOperationRequestHandler : public WorkflowRequestHandler<GetStoreOperationRequest^, GetStoreOperationResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetStoreOperationRequest](getstoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetStoreOperationResponse](getstoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoreOperationRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

