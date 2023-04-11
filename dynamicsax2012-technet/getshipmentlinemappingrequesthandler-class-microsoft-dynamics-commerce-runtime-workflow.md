---
title: GetShipmentLineMappingRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetShipmentLineMappingRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentLineMappingRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getshipmentlinemappingrequesthandler(v=AX.60)
ms:contentKeyID: 62211279
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentLineMappingRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentLineMappingRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for reading shipments.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetShipmentLineMappingRequestHandler _
    Inherits WorkflowRequestHandler(Of GetShipmentLineMappingRequest, GetShipmentLineMappingResponse)
'Usage
Dim instance As GetShipmentLineMappingRequestHandler
```

``` csharp
public sealed class GetShipmentLineMappingRequestHandler : WorkflowRequestHandler<GetShipmentLineMappingRequest, GetShipmentLineMappingResponse>
```

``` c++
public ref class GetShipmentLineMappingRequestHandler sealed : public WorkflowRequestHandler<GetShipmentLineMappingRequest^, GetShipmentLineMappingResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetShipmentLineMappingRequest](getshipmentlinemappingrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetShipmentLineMappingResponse](getshipmentlinemappingresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShipmentLineMappingRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

