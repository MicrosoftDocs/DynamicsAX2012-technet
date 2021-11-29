---
title: GetStockCountRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetStockCountRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStockCountRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getstockcountrequesthandler(v=AX.60)
ms:contentKeyID: 62211719
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStockCountRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for retrieving StockCount journals and associated Transactions from RetailServer db.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetStockCountRequestHandler _
    Inherits WorkflowRequestHandler(Of GetStockCountRequest, GetStockCountResponse)
'Usage
Dim instance As GetStockCountRequestHandler
```

``` csharp
public sealed class GetStockCountRequestHandler : WorkflowRequestHandler<GetStockCountRequest, GetStockCountResponse>
```

``` c++
public ref class GetStockCountRequestHandler sealed : public WorkflowRequestHandler<GetStockCountRequest^, GetStockCountResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetStockCountRequest](getstockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetStockCountResponse](getstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStockCountRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

