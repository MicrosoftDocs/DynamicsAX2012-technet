---
title: GetActiveProductPriceRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetActiveProductPriceRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetActiveProductPriceRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getactiveproductpricerequesthandler(v=AX.60)
ms:contentKeyID: 62202831
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetActiveProductPriceRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveProductPriceRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves the price of an item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetActiveProductPriceRequestHandler _
    Inherits WorkflowRequestHandler(Of GetActiveProductPriceRequest, GetActiveProductPriceResponse)
'Usage
Dim instance As GetActiveProductPriceRequestHandler
```

``` csharp
public sealed class GetActiveProductPriceRequestHandler : WorkflowRequestHandler<GetActiveProductPriceRequest, GetActiveProductPriceResponse>
```

``` c++
public ref class GetActiveProductPriceRequestHandler sealed : public WorkflowRequestHandler<GetActiveProductPriceRequest^, GetActiveProductPriceResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetActiveProductPriceRequest](getactiveproductpricerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetActiveProductPriceResponse](getactiveproductpriceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetActiveProductPriceRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

