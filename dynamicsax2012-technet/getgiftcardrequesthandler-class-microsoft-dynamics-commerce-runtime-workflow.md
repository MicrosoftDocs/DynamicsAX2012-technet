---
title: GetGiftCardRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetGiftCardRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetGiftCardRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getgiftcardrequesthandler(v=AX.60)
ms:contentKeyID: 62208517
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetGiftCardRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetGiftCardRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles workflow to get gift card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetGiftCardRequestHandler _
    Inherits WorkflowRequestHandler(Of GetGiftCardRequest, GetGiftCardResponse)
'Usage
Dim instance As GetGiftCardRequestHandler
```

``` csharp
public sealed class GetGiftCardRequestHandler : WorkflowRequestHandler<GetGiftCardRequest, GetGiftCardResponse>
```

``` c++
public ref class GetGiftCardRequestHandler sealed : public WorkflowRequestHandler<GetGiftCardRequest^, GetGiftCardResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetGiftCardRequest](getgiftcardrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetGiftCardResponse](getgiftcardresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetGiftCardRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

