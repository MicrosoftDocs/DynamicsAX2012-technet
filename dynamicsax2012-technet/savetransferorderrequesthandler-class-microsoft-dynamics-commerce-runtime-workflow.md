---
title: SaveTransferOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveTransferOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveTransferOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.savetransferorderrequesthandler(v=AX.60)
ms:contentKeyID: 62212190
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveTransferOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SaveTransferOrderRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The class to handle SavePickingReceivingCountRequest.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SaveTransferOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of SaveTransferOrderRequest, NullResponse)
'Usage
Dim instance As SaveTransferOrderRequestHandler
```

``` csharp
public sealed class SaveTransferOrderRequestHandler : WorkflowRequestHandler<SaveTransferOrderRequest, NullResponse>
```

``` c++
public ref class SaveTransferOrderRequestHandler sealed : public WorkflowRequestHandler<SaveTransferOrderRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SaveTransferOrderRequest](savetransferorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveTransferOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

