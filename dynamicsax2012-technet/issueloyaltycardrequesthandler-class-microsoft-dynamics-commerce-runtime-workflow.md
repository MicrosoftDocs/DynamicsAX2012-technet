---
title: IssueLoyaltyCardRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: IssueLoyaltyCardRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueLoyaltyCardRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.issueloyaltycardrequesthandler(v=AX.60)
ms:contentKeyID: 62212368
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueLoyaltyCardRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# IssueLoyaltyCardRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the request for issuing a loyalty card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class IssueLoyaltyCardRequestHandler _
    Inherits WorkflowRequestHandler(Of IssueLoyaltyCardRequest, IssueLoyaltyCardResponse)
'Usage
Dim instance As IssueLoyaltyCardRequestHandler
```

``` csharp
public sealed class IssueLoyaltyCardRequestHandler : WorkflowRequestHandler<IssueLoyaltyCardRequest, IssueLoyaltyCardResponse>
```

``` c++
public ref class IssueLoyaltyCardRequestHandler sealed : public WorkflowRequestHandler<IssueLoyaltyCardRequest^, IssueLoyaltyCardResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[IssueLoyaltyCardRequest](issueloyaltycardrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [IssueLoyaltyCardResponse](issueloyaltycardresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueLoyaltyCardRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

