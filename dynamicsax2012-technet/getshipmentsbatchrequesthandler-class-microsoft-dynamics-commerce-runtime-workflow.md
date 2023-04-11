---
title: GetShipmentsBatchRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetShipmentsBatchRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentsBatchRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getshipmentsbatchrequesthandler(v=AX.60)
ms:contentKeyID: 62211908
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentsBatchRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentsBatchRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for reading shipments.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetShipmentsBatchRequestHandler _
    Inherits WorkflowRequestHandler(Of GetShipmentsBatchRequest, GetShipmentsBatchResponse)
'Usage
Dim instance As GetShipmentsBatchRequestHandler
```

``` csharp
public sealed class GetShipmentsBatchRequestHandler : WorkflowRequestHandler<GetShipmentsBatchRequest, GetShipmentsBatchResponse>
```

``` c++
public ref class GetShipmentsBatchRequestHandler sealed : public WorkflowRequestHandler<GetShipmentsBatchRequest^, GetShipmentsBatchResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetShipmentsBatchRequest](getshipmentsbatchrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetShipmentsBatchResponse](getshipmentsbatchresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentsBatchRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

