---
title: GetChangedProductsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetChangedProductsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChangedProductsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getchangedproductsrequesthandler(v=AX.60)
ms:contentKeyID: 62207072
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChangedProductsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetChangedProductsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves the collection of products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetChangedProductsRequestHandler _
    Inherits WorkflowRequestHandler(Of ChangedProductsSearchRequest, ChangedProductsSearchResponse)
'Usage
Dim instance As GetChangedProductsRequestHandler
```

``` csharp
public sealed class GetChangedProductsRequestHandler : WorkflowRequestHandler<ChangedProductsSearchRequest, ChangedProductsSearchResponse>
```

``` c++
public ref class GetChangedProductsRequestHandler sealed : public WorkflowRequestHandler<ChangedProductsSearchRequest^, ChangedProductsSearchResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[ChangedProductsSearchRequest](changedproductssearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [ChangedProductsSearchResponse](changedproductssearchresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChangedProductsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

