---
title: GetEmployeePermissionRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetEmployeePermissionRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetEmployeePermissionRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getemployeepermissionrequesthandler(v=AX.60)
ms:contentKeyID: 62206402
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetEmployeePermissionRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeePermissionRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to get employee permission.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetEmployeePermissionRequestHandler _
    Inherits WorkflowRequestHandler(Of GetEmployeePermissionsRequest, GetEmployeePermissionsResponse)
'Usage
Dim instance As GetEmployeePermissionRequestHandler
```

``` csharp
public sealed class GetEmployeePermissionRequestHandler : WorkflowRequestHandler<GetEmployeePermissionsRequest, GetEmployeePermissionsResponse>
```

``` c++
public ref class GetEmployeePermissionRequestHandler sealed : public WorkflowRequestHandler<GetEmployeePermissionsRequest^, GetEmployeePermissionsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetEmployeePermissionsRequest](getemployeepermissionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetEmployeePermissionsResponse](getemployeepermissionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetEmployeePermissionRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

