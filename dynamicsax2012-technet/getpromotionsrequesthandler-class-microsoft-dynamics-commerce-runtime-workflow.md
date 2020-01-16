---
title: GetPromotionsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetPromotionsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPromotionsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getpromotionsrequesthandler(v=AX.60)
ms:contentKeyID: 62208446
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPromotionsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetPromotionsRequestHandler Class

Handles workflow for GetPromotionsForCart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetPromotionsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetPromotionsRequest, GetPromotionsResponse)
'Usage
Dim instance As GetPromotionsRequestHandler
```

``` csharp
public sealed class GetPromotionsRequestHandler : WorkflowRequestHandler<GetPromotionsRequest, GetPromotionsResponse>
```

``` c++
public ref class GetPromotionsRequestHandler sealed : public WorkflowRequestHandler<GetPromotionsRequest^, GetPromotionsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetPromotionsRequest](getpromotionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetPromotionsResponse](getpromotionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPromotionsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

