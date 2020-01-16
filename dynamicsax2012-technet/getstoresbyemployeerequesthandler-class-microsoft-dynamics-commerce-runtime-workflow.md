---
title: GetStoresByEmployeeRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetStoresByEmployeeRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoresByEmployeeRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getstoresbyemployeerequesthandler(v=AX.60)
ms:contentKeyID: 62213492
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoresByEmployeeRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetStoresByEmployeeRequestHandler Class

Encapsulates the workflow to process the employee time clock registration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetStoresByEmployeeRequestHandler _
    Inherits WorkflowRequestHandler(Of GetStoresByEmployeeRequest, GetStoresByEmployeeResponse)
'Usage
Dim instance As GetStoresByEmployeeRequestHandler
```

``` csharp
public class GetStoresByEmployeeRequestHandler : WorkflowRequestHandler<GetStoresByEmployeeRequest, GetStoresByEmployeeResponse>
```

``` c++
public ref class GetStoresByEmployeeRequestHandler : public WorkflowRequestHandler<GetStoresByEmployeeRequest^, GetStoresByEmployeeResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetStoresByEmployeeRequest](getstoresbyemployeerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetStoresByEmployeeResponse](getstoresbyemployeeresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoresByEmployeeRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

