---
title: SubmitSalesTransactionRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SubmitSalesTransactionRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitSalesTransactionRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.submitsalestransactionrequesthandler(v=AX.60)
ms:contentKeyID: 62210752
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitSalesTransactionRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SubmitSalesTransactionRequestHandler Class

Handler for submit sales transaction request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SubmitSalesTransactionRequestHandler _
    Inherits WorkflowRequestHandler(Of SubmitSalesTransactionRequest, SubmitSalesTransactionResponse)
'Usage
Dim instance As SubmitSalesTransactionRequestHandler
```

``` csharp
public sealed class SubmitSalesTransactionRequestHandler : WorkflowRequestHandler<SubmitSalesTransactionRequest, SubmitSalesTransactionResponse>
```

``` c++
public ref class SubmitSalesTransactionRequestHandler sealed : public WorkflowRequestHandler<SubmitSalesTransactionRequest^, SubmitSalesTransactionResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SubmitSalesTransactionRequest](submitsalestransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SubmitSalesTransactionResponse](submitsalestransactionresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitSalesTransactionRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

