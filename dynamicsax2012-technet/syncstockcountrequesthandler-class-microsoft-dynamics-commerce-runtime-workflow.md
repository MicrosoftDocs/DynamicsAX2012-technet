---
title: SyncStockCountRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SyncStockCountRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SyncStockCountRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.syncstockcountrequesthandler(v=AX.60)
ms:contentKeyID: 62212315
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SyncStockCountRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SyncStockCountRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for syncing StockCount journals and associated Transactions from AX to RetailServer db.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SyncStockCountRequestHandler _
    Inherits WorkflowRequestHandler(Of SyncStockCountRequest, SyncStockCountResponse)
'Usage
Dim instance As SyncStockCountRequestHandler
```

``` csharp
public sealed class SyncStockCountRequestHandler : WorkflowRequestHandler<SyncStockCountRequest, SyncStockCountResponse>
```

``` c++
public ref class SyncStockCountRequestHandler sealed : public WorkflowRequestHandler<SyncStockCountRequest^, SyncStockCountResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SyncStockCountRequest](syncstockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SyncStockCountResponse](syncstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SyncStockCountRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

