---
title: GetCustomerLoyaltyCardsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCustomerLoyaltyCardsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerLoyaltyCardsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcustomerloyaltycardsrequesthandler(v=AX.60)
ms:contentKeyID: 62208546
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerLoyaltyCardsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerLoyaltyCardsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the request for getting the loyalty cards of a customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetCustomerLoyaltyCardsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCustomerLoyaltyCardsRequest, GetCustomerLoyaltyCardsResponse)
'Usage
Dim instance As GetCustomerLoyaltyCardsRequestHandler
```

``` csharp
public sealed class GetCustomerLoyaltyCardsRequestHandler : WorkflowRequestHandler<GetCustomerLoyaltyCardsRequest, GetCustomerLoyaltyCardsResponse>
```

``` c++
public ref class GetCustomerLoyaltyCardsRequestHandler sealed : public WorkflowRequestHandler<GetCustomerLoyaltyCardsRequest^, GetCustomerLoyaltyCardsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCustomerLoyaltyCardsRequest](getcustomerloyaltycardsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCustomerLoyaltyCardsResponse](getcustomerloyaltycardsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerLoyaltyCardsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

