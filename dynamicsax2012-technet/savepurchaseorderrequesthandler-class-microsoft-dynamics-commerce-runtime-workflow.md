---
title: SavePurchaseOrderRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SavePurchaseOrderRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SavePurchaseOrderRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.savepurchaseorderrequesthandler(v=AX.60)
ms:contentKeyID: 62214098
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SavePurchaseOrderRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SavePurchaseOrderRequestHandler Class

The class to handle SavePickingReceivingCountRequest.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SavePurchaseOrderRequestHandler _
    Inherits WorkflowRequestHandler(Of SavePurchaseOrderRequest, NullResponse)
'Usage
Dim instance As SavePurchaseOrderRequestHandler
```

``` csharp
public sealed class SavePurchaseOrderRequestHandler : WorkflowRequestHandler<SavePurchaseOrderRequest, NullResponse>
```

``` c++
public ref class SavePurchaseOrderRequestHandler sealed : public WorkflowRequestHandler<SavePurchaseOrderRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SavePurchaseOrderRequest](savepurchaseorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SavePurchaseOrderRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

