---
title: GetShipmentPublishingStatusRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetShipmentPublishingStatusRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentPublishingStatusRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getshipmentpublishingstatusrequesthandler(v=AX.60)
ms:contentKeyID: 62206708
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentPublishingStatusRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentPublishingStatusRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for reading shipments.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetShipmentPublishingStatusRequestHandler _
    Inherits WorkflowRequestHandler(Of GetShipmentPublishingStatusRequest, GetShipmentPublishingStatusResponse)
'Usage
Dim instance As GetShipmentPublishingStatusRequestHandler
```

``` csharp
public sealed class GetShipmentPublishingStatusRequestHandler : WorkflowRequestHandler<GetShipmentPublishingStatusRequest, GetShipmentPublishingStatusResponse>
```

``` c++
public ref class GetShipmentPublishingStatusRequestHandler sealed : public WorkflowRequestHandler<GetShipmentPublishingStatusRequest^, GetShipmentPublishingStatusResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetShipmentPublishingStatusRequest](getshipmentpublishingstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetShipmentPublishingStatusResponse](getshipmentpublishingstatusresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentPublishingStatusRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

