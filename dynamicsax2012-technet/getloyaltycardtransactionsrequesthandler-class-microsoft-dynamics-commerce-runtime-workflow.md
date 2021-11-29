---
title: GetLoyaltyCardTransactionsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetLoyaltyCardTransactionsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardTransactionsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getloyaltycardtransactionsrequesthandler(v=AX.60)
ms:contentKeyID: 62212768
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardTransactionsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactionsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the request for getting the loyalty card transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetLoyaltyCardTransactionsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetLoyaltyCardTransactionsRequest, GetLoyaltyCardTransactionsResponse)
'Usage
Dim instance As GetLoyaltyCardTransactionsRequestHandler
```

``` csharp
public sealed class GetLoyaltyCardTransactionsRequestHandler : WorkflowRequestHandler<GetLoyaltyCardTransactionsRequest, GetLoyaltyCardTransactionsResponse>
```

``` c++
public ref class GetLoyaltyCardTransactionsRequestHandler sealed : public WorkflowRequestHandler<GetLoyaltyCardTransactionsRequest^, GetLoyaltyCardTransactionsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetLoyaltyCardTransactionsRequest](getloyaltycardtransactionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetLoyaltyCardTransactionsResponse](getloyaltycardtransactionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardTransactionsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

