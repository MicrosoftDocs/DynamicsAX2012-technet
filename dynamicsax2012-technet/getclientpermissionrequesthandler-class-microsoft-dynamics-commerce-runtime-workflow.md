---
title: GetClientPermissionRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetClientPermissionRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetClientPermissionRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getclientpermissionrequesthandler(v=AX.60)
ms:contentKeyID: 62211057
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetClientPermissionRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetClientPermissionRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to get employee permission.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetClientPermissionRequestHandler _
    Inherits WorkflowRequestHandler(Of GetOperationPermissionsRequest, GetOperationPermissionsResponse)
'Usage
Dim instance As GetClientPermissionRequestHandler
```

``` csharp
public sealed class GetClientPermissionRequestHandler : WorkflowRequestHandler<GetOperationPermissionsRequest, GetOperationPermissionsResponse>
```

``` c++
public ref class GetClientPermissionRequestHandler sealed : public WorkflowRequestHandler<GetOperationPermissionsRequest^, GetOperationPermissionsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetOperationPermissionsRequest](getoperationpermissionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetOperationPermissionsResponse](getoperationpermissionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetClientPermissionRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

