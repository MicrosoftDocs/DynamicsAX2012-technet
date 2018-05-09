---
title: CreateOrUpdateCartRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CreateOrUpdateCartRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateOrUpdateCartRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.createorupdatecartrequesthandler(v=AX.60)
ms:contentKeyID: 49825763
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateOrUpdateCartRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrUpdateCartRequestHandler Class

Saves a shopping cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CreateOrUpdateCartRequestHandler _
    Inherits WorkflowRequestHandler(Of SaveCartRequest, SaveCartResponse)
'Usage
Dim instance As CreateOrUpdateCartRequestHandler
```

``` csharp
public sealed class CreateOrUpdateCartRequestHandler : WorkflowRequestHandler<SaveCartRequest, SaveCartResponse>
```

``` c++
public ref class CreateOrUpdateCartRequestHandler sealed : public WorkflowRequestHandler<SaveCartRequest^, SaveCartResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SaveCartRequest](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SaveCartResponse](savecartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateOrUpdateCartRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

