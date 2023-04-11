---
title: SaveStockCountRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveStockCountRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStockCountRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.savestockcountrequesthandler(v=AX.60)
ms:contentKeyID: 62214030
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStockCountRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SaveStockCountRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for save/ commit StockCount journal Transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SaveStockCountRequestHandler _
    Inherits WorkflowRequestHandler(Of SaveStockCountRequest, SaveStockCountResponse)
'Usage
Dim instance As SaveStockCountRequestHandler
```

``` csharp
public sealed class SaveStockCountRequestHandler : WorkflowRequestHandler<SaveStockCountRequest, SaveStockCountResponse>
```

``` c++
public ref class SaveStockCountRequestHandler sealed : public WorkflowRequestHandler<SaveStockCountRequest^, SaveStockCountResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SaveStockCountRequest](savestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SaveStockCountResponse](savestockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStockCountRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

