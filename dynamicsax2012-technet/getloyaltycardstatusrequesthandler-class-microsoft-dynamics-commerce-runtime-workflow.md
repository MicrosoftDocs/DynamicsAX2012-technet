---
title: GetLoyaltyCardStatusRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetLoyaltyCardStatusRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardStatusRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getloyaltycardstatusrequesthandler(v=AX.60)
ms:contentKeyID: 62204402
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardStatusRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardStatusRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the request for getting the status of a loyalty card including card tiers and reward points status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetLoyaltyCardStatusRequestHandler _
    Inherits WorkflowRequestHandler(Of GetLoyaltyCardStatusRequest, GetLoyaltyCardStatusResponse)
'Usage
Dim instance As GetLoyaltyCardStatusRequestHandler
```

``` csharp
public sealed class GetLoyaltyCardStatusRequestHandler : WorkflowRequestHandler<GetLoyaltyCardStatusRequest, GetLoyaltyCardStatusResponse>
```

``` c++
public ref class GetLoyaltyCardStatusRequestHandler sealed : public WorkflowRequestHandler<GetLoyaltyCardStatusRequest^, GetLoyaltyCardStatusResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetLoyaltyCardStatusRequest](getloyaltycardstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetLoyaltyCardStatusResponse](getloyaltycardstatusresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardStatusRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

