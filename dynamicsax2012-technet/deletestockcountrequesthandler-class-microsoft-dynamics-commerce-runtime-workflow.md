---
title: DeleteStockCountRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: DeleteStockCountRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteStockCountRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.deletestockcountrequesthandler(v=AX.60)
ms:contentKeyID: 62207273
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteStockCountRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# DeleteStockCountRequestHandler Class

Handler for deleting StockCount journals and associated Transactions from RetailServer db.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class DeleteStockCountRequestHandler _
    Inherits WorkflowRequestHandler(Of DeleteStockCountRequest, NullResponse)
'Usage
Dim instance As DeleteStockCountRequestHandler
```

``` csharp
public sealed class DeleteStockCountRequestHandler : WorkflowRequestHandler<DeleteStockCountRequest, NullResponse>
```

``` c++
public ref class DeleteStockCountRequestHandler sealed : public WorkflowRequestHandler<DeleteStockCountRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[DeleteStockCountRequest](deletestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteStockCountRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

