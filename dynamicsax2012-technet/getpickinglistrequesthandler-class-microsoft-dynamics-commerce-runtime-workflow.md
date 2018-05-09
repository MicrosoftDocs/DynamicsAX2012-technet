---
title: GetPickingListRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetPickingListRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPickingListRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getpickinglistrequesthandler(v=AX.60)
ms:contentKeyID: 62212562
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPickingListRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetPickingListRequestHandler Class

The class to handle GetPickingListRequest.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetPickingListRequestHandler _
    Inherits WorkflowRequestHandler(Of GetPickingListRequest, GetPickingListResponse)
'Usage
Dim instance As GetPickingListRequestHandler
```

``` csharp
public sealed class GetPickingListRequestHandler : WorkflowRequestHandler<GetPickingListRequest, GetPickingListResponse>
```

``` c++
public ref class GetPickingListRequestHandler sealed : public WorkflowRequestHandler<GetPickingListRequest^, GetPickingListResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetPickingListRequest](getpickinglistrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetPickingListResponse](getpickinglistresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPickingListRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

