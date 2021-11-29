---
title: EndReadChangedProductsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: EndReadChangedProductsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.EndReadChangedProductsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.endreadchangedproductsrequesthandler(v=AX.60)
ms:contentKeyID: 62214931
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EndReadChangedProductsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# EndReadChangedProductsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles request to end read changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class EndReadChangedProductsRequestHandler _
    Inherits WorkflowRequestHandler(Of EndReadChangedProductsRequest, EndReadChangedProductsResponse)
'Usage
Dim instance As EndReadChangedProductsRequestHandler
```

``` csharp
public class EndReadChangedProductsRequestHandler : WorkflowRequestHandler<EndReadChangedProductsRequest, EndReadChangedProductsResponse>
```

``` c++
public ref class EndReadChangedProductsRequestHandler : public WorkflowRequestHandler<EndReadChangedProductsRequest^, EndReadChangedProductsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[EndReadChangedProductsRequest](endreadchangedproductsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [EndReadChangedProductsResponse](endreadchangedproductsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.EndReadChangedProductsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

