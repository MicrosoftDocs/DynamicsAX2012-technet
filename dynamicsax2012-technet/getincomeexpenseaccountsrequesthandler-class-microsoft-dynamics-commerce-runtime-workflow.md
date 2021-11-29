---
title: GetIncomeExpenseAccountsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetIncomeExpenseAccountsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetIncomeExpenseAccountsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getincomeexpenseaccountsrequesthandler(v=AX.60)
ms:contentKeyID: 62208790
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetIncomeExpenseAccountsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetIncomeExpenseAccountsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Workflow to handle the income or expense accounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetIncomeExpenseAccountsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetIncomeExpenseAccountsRequest, GetIncomeExpenseAccountsResponse)
'Usage
Dim instance As GetIncomeExpenseAccountsRequestHandler
```

``` csharp
public class GetIncomeExpenseAccountsRequestHandler : WorkflowRequestHandler<GetIncomeExpenseAccountsRequest, GetIncomeExpenseAccountsResponse>
```

``` c++
public ref class GetIncomeExpenseAccountsRequestHandler : public WorkflowRequestHandler<GetIncomeExpenseAccountsRequest^, GetIncomeExpenseAccountsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetIncomeExpenseAccountsRequest](getincomeexpenseaccountsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetIncomeExpenseAccountsResponse](getincomeexpenseaccountsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetIncomeExpenseAccountsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

