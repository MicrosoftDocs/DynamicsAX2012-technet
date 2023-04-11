---
title: GetAvailableShiftsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetAvailableShiftsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableShiftsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getavailableshiftsrequesthandler(v=AX.60)
ms:contentKeyID: 62208986
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableShiftsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetAvailableShiftsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to get available stores for device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetAvailableShiftsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetAvailableShiftsRequest, GetAvailableShiftsResponse)
'Usage
Dim instance As GetAvailableShiftsRequestHandler
```

``` csharp
public sealed class GetAvailableShiftsRequestHandler : WorkflowRequestHandler<GetAvailableShiftsRequest, GetAvailableShiftsResponse>
```

``` c++
public ref class GetAvailableShiftsRequestHandler sealed : public WorkflowRequestHandler<GetAvailableShiftsRequest^, GetAvailableShiftsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetAvailableShiftsRequest](getavailableshiftsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetAvailableShiftsResponse](getavailableshiftsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableShiftsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

