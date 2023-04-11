---
title: GetCreditMemoRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCreditMemoRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCreditMemoRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcreditmemorequesthandler(v=AX.60)
ms:contentKeyID: 62214370
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCreditMemoRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCreditMemoRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles workflow to get gift card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetCreditMemoRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCreditMemoRequest, GetCreditMemoResponse)
'Usage
Dim instance As GetCreditMemoRequestHandler
```

``` csharp
public sealed class GetCreditMemoRequestHandler : WorkflowRequestHandler<GetCreditMemoRequest, GetCreditMemoResponse>
```

``` c++
public ref class GetCreditMemoRequestHandler sealed : public WorkflowRequestHandler<GetCreditMemoRequest^, GetCreditMemoResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCreditMemoRequest](getcreditmemorequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCreditMemoResponse](getcreditmemoresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCreditMemoRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

