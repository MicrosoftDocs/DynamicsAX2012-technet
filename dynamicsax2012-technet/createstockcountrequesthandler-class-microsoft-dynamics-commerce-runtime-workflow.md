---
title: CreateStockCountRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CreateStockCountRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateStockCountRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.createstockcountrequesthandler(v=AX.60)
ms:contentKeyID: 62211256
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateStockCountRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# CreateStockCountRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for creating StockCount journals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CreateStockCountRequestHandler _
    Inherits WorkflowRequestHandler(Of CreateStockCountRequest, CreateStockCountResponse)
'Usage
Dim instance As CreateStockCountRequestHandler
```

``` csharp
public sealed class CreateStockCountRequestHandler : WorkflowRequestHandler<CreateStockCountRequest, CreateStockCountResponse>
```

``` c++
public ref class CreateStockCountRequestHandler sealed : public WorkflowRequestHandler<CreateStockCountRequest^, CreateStockCountResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[CreateStockCountRequest](createstockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [CreateStockCountResponse](createstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateStockCountRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

