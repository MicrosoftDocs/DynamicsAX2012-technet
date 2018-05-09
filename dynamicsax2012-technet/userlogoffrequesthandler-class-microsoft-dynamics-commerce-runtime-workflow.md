---
title: UserLogOffRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: UserLogOffRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.UserLogOffRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.userlogoffrequesthandler(v=AX.60)
ms:contentKeyID: 62202623
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.UserLogOffRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# UserLogOffRequestHandler Class

Encapsulates the workflow required to do user authentication.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class UserLogOffRequestHandler _
    Inherits WorkflowRequestHandler(Of UserLogOffRequest, NullResponse)
'Usage
Dim instance As UserLogOffRequestHandler
```

``` csharp
public sealed class UserLogOffRequestHandler : WorkflowRequestHandler<UserLogOffRequest, NullResponse>
```

``` c++
public ref class UserLogOffRequestHandler sealed : public WorkflowRequestHandler<UserLogOffRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[UserLogOffRequest](userlogoffrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.UserLogOffRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

