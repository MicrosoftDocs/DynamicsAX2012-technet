---
title: GetProductsInCartRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetProductsInCartRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductsInCartRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getproductsincartrequesthandler(v=AX.60)
ms:contentKeyID: 62210000
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductsInCartRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsInCartRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the products used in context of the shopping cart specified by cart id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetProductsInCartRequestHandler _
    Inherits WorkflowRequestHandler(Of GetProductsInCartRequest, GetProductsInCartResponse)
'Usage
Dim instance As GetProductsInCartRequestHandler
```

``` csharp
public sealed class GetProductsInCartRequestHandler : WorkflowRequestHandler<GetProductsInCartRequest, GetProductsInCartResponse>
```

``` c++
public ref class GetProductsInCartRequestHandler sealed : public WorkflowRequestHandler<GetProductsInCartRequest^, GetProductsInCartResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetProductsInCartRequest](getproductsincartrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetProductsInCartResponse](getproductsincartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductsInCartRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

