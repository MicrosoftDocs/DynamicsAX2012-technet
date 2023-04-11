---
title: GetSalesTaxGroupsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetSalesTaxGroupsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSalesTaxGroupsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getsalestaxgroupsrequesthandler(v=AX.60)
ms:contentKeyID: 62204235
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSalesTaxGroupsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesTaxGroupsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve sales tax groups associated with AX company.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetSalesTaxGroupsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetSalesTaxGroupsRequest, GetSalesTaxGroupsResponse)
'Usage
Dim instance As GetSalesTaxGroupsRequestHandler
```

``` csharp
public class GetSalesTaxGroupsRequestHandler : WorkflowRequestHandler<GetSalesTaxGroupsRequest, GetSalesTaxGroupsResponse>
```

``` c++
public ref class GetSalesTaxGroupsRequestHandler : public WorkflowRequestHandler<GetSalesTaxGroupsRequest^, GetSalesTaxGroupsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetSalesTaxGroupsRequest](getsalestaxgroupsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetSalesTaxGroupsResponse](getsalestaxgroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSalesTaxGroupsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

