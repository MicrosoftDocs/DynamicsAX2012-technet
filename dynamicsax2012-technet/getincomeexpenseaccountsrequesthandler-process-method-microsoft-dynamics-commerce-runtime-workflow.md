---
title: GetIncomeExpenseAccountsRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetIncomeExpenseAccountsRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getincomeexpenseaccountsrequesthandler.process(v=AX.60)
ms:contentKeyID: 62212191
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetIncomeExpenseAccountsRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow to get the income or expense accounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetIncomeExpenseAccountsRequest _
) As GetIncomeExpenseAccountsResponse
'Usage
Dim request As GetIncomeExpenseAccountsRequest
Dim returnValue As GetIncomeExpenseAccountsResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetIncomeExpenseAccountsResponse Process(
    GetIncomeExpenseAccountsRequest request
)
```

``` c++
protected:
virtual GetIncomeExpenseAccountsResponse^ Process(
    GetIncomeExpenseAccountsRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsRequest](getincomeexpenseaccountsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsResponse](getincomeexpenseaccountsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
Instance of [GetIncomeExpenseAccountsResponse](getincomeexpenseaccountsresponse-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[GetIncomeExpenseAccountsRequestHandler Class](getincomeexpenseaccountsrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

