---
title: GetWarehouseDetailsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetWarehouseDetailsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetWarehouseDetailsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getwarehousedetailsrequesthandler(v=AX.60)
ms:contentKeyID: 62214647
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetWarehouseDetailsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetWarehouseDetailsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles workflow for GetWarehouseDetails.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetWarehouseDetailsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetWarehouseDetailsRequest, GetWarehouseDetailsResponse)
'Usage
Dim instance As GetWarehouseDetailsRequestHandler
```

``` csharp
public sealed class GetWarehouseDetailsRequestHandler : WorkflowRequestHandler<GetWarehouseDetailsRequest, GetWarehouseDetailsResponse>
```

``` c++
public ref class GetWarehouseDetailsRequestHandler sealed : public WorkflowRequestHandler<GetWarehouseDetailsRequest^, GetWarehouseDetailsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetWarehouseDetailsRequest](getwarehousedetailsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetWarehouseDetailsResponse](getwarehousedetailsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetWarehouseDetailsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

