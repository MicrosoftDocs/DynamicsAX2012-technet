---
title: SearchProductsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SearchProductsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SearchProductsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.searchproductsrequesthandler(v=AX.60)
ms:contentKeyID: 62213745
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SearchProductsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SearchProductsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves the collection of products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SearchProductsRequestHandler _
    Inherits WorkflowRequestHandler(Of ProductSearchRequest, ProductSearchResponse)
'Usage
Dim instance As SearchProductsRequestHandler
```

``` csharp
public sealed class SearchProductsRequestHandler : WorkflowRequestHandler<ProductSearchRequest, ProductSearchResponse>
```

``` c++
public ref class SearchProductsRequestHandler sealed : public WorkflowRequestHandler<ProductSearchRequest^, ProductSearchResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[ProductSearchRequest](productsearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [ProductSearchResponse](productsearchresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SearchProductsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

