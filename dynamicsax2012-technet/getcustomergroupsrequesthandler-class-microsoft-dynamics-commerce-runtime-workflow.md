---
title: GetCustomerGroupsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCustomerGroupsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerGroupsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcustomergroupsrequesthandler(v=AX.60)
ms:contentKeyID: 62214571
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerGroupsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerGroupsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve the customer groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetCustomerGroupsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCustomerGroupsRequest, GetCustomerGroupsResponse)
'Usage
Dim instance As GetCustomerGroupsRequestHandler
```

``` csharp
public class GetCustomerGroupsRequestHandler : WorkflowRequestHandler<GetCustomerGroupsRequest, GetCustomerGroupsResponse>
```

``` c++
public ref class GetCustomerGroupsRequestHandler : public WorkflowRequestHandler<GetCustomerGroupsRequest^, GetCustomerGroupsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCustomerGroupsRequest](getcustomergroupsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCustomerGroupsResponse](getcustomergroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerGroupsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

