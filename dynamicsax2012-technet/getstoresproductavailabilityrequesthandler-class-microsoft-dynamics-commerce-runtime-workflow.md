---
title: GetStoresProductAvailabilityRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetStoresProductAvailabilityRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoresProductAvailabilityRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getstoresproductavailabilityrequesthandler(v=AX.60)
ms:contentKeyID: 49833847
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoresProductAvailabilityRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetStoresProductAvailabilityRequestHandler Class

Encapsulates the workflow required to get product availability information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetStoresProductAvailabilityRequestHandler _
    Inherits WorkflowRequestHandler(Of GetStoreProductAvailabilityRequest, GetStoreProductAvailabilityResponse)
'Usage
Dim instance As GetStoresProductAvailabilityRequestHandler
```

``` csharp
public sealed class GetStoresProductAvailabilityRequestHandler : WorkflowRequestHandler<GetStoreProductAvailabilityRequest, GetStoreProductAvailabilityResponse>
```

``` c++
public ref class GetStoresProductAvailabilityRequestHandler sealed : public WorkflowRequestHandler<GetStoreProductAvailabilityRequest^, GetStoreProductAvailabilityResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetStoreProductAvailabilityRequest](getstoreproductavailabilityrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetStoreProductAvailabilityResponse](getstoreproductavailabilityresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoresProductAvailabilityRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

