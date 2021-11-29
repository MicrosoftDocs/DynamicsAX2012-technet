---
title: GetListingAvailableQuantitiesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetListingAvailableQuantitiesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetListingAvailableQuantitiesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getlistingavailablequantitiesrequesthandler(v=AX.60)
ms:contentKeyID: 49855570
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetListingAvailableQuantitiesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetListingAvailableQuantitiesRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves quantities of provided listings from the default warehouse associated with the customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetListingAvailableQuantitiesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetListingAvailableQuantitiesRequest, GetListingAvailableQuantitiesResponse)
'Usage
Dim instance As GetListingAvailableQuantitiesRequestHandler
```

``` csharp
public sealed class GetListingAvailableQuantitiesRequestHandler : WorkflowRequestHandler<GetListingAvailableQuantitiesRequest, GetListingAvailableQuantitiesResponse>
```

``` c++
public ref class GetListingAvailableQuantitiesRequestHandler sealed : public WorkflowRequestHandler<GetListingAvailableQuantitiesRequest^, GetListingAvailableQuantitiesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetListingAvailableQuantitiesRequest](getlistingavailablequantitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetListingAvailableQuantitiesResponse](getlistingavailablequantitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetListingAvailableQuantitiesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

