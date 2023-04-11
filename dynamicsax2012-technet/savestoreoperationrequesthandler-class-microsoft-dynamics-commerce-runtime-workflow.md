---
title: SaveStoreOperationRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveStoreOperationRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStoreOperationRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.savestoreoperationrequesthandler(v=AX.60)
ms:contentKeyID: 62211053
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStoreOperationRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SaveStoreOperationRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Save all incoming non-sale transaction from store operations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class SaveStoreOperationRequestHandler _
    Inherits WorkflowRequestHandler(Of SaveStoreOperationRequest, SaveStoreOperationResponse)
'Usage
Dim instance As SaveStoreOperationRequestHandler
```

``` csharp
public class SaveStoreOperationRequestHandler : WorkflowRequestHandler<SaveStoreOperationRequest, SaveStoreOperationResponse>
```

``` c++
public ref class SaveStoreOperationRequestHandler : public WorkflowRequestHandler<SaveStoreOperationRequest^, SaveStoreOperationResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SaveStoreOperationRequest](savestoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SaveStoreOperationResponse](savestoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStoreOperationRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

