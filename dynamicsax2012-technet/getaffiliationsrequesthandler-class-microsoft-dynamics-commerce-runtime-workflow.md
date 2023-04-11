---
title: GetAffiliationsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetAffiliationsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAffiliationsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getaffiliationsrequesthandler(v=AX.60)
ms:contentKeyID: 62204540
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAffiliationsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetAffiliationsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve affiliations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetAffiliationsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetAffiliationsRequest, GetAffiliationsResponse)
'Usage
Dim instance As GetAffiliationsRequestHandler
```

``` csharp
public sealed class GetAffiliationsRequestHandler : WorkflowRequestHandler<GetAffiliationsRequest, GetAffiliationsResponse>
```

``` c++
public ref class GetAffiliationsRequestHandler sealed : public WorkflowRequestHandler<GetAffiliationsRequest^, GetAffiliationsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetAffiliationsRequest](getaffiliationsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetAffiliationsResponse](getaffiliationsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAffiliationsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

