---
title: GetCustomersRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCustomersRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomersRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getcustomersrequesthandler(v=AX.60)
ms:contentKeyID: 49830250
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomersRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomersRequestHandler Class

GetCustomersRequest class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetCustomersRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCustomersRequest, GetCustomersResponse)
'Usage
Dim instance As GetCustomersRequestHandler
```

``` csharp
public sealed class GetCustomersRequestHandler : WorkflowRequestHandler<GetCustomersRequest, GetCustomersResponse>
```

``` c++
public ref class GetCustomersRequestHandler sealed : public WorkflowRequestHandler<GetCustomersRequest^, GetCustomersResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCustomersRequest](getcustomersrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCustomersResponse](getcustomersresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomersRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

