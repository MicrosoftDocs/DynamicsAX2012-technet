---
title: DeleteCartRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: DeleteCartRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteCartRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.deletecartrequesthandler(v=AX.60)
ms:contentKeyID: 49838546
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteCartRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# DeleteCartRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes a previously saved shopping cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class DeleteCartRequestHandler _
    Inherits WorkflowRequestHandler(Of DeleteCartRequest, NullResponse)
'Usage
Dim instance As DeleteCartRequestHandler
```

``` csharp
public sealed class DeleteCartRequestHandler : WorkflowRequestHandler<DeleteCartRequest, NullResponse>
```

``` c++
public ref class DeleteCartRequestHandler sealed : public WorkflowRequestHandler<DeleteCartRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[DeleteCartRequest](deletecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteCartRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

