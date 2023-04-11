---
title: UserResetPasswordRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: UserResetPasswordRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.UserResetPasswordRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.userresetpasswordrequesthandler(v=AX.60)
ms:contentKeyID: 62215053
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.UserResetPasswordRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# UserResetPasswordRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to do user authentication.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class UserResetPasswordRequestHandler _
    Inherits WorkflowRequestHandler(Of UserResetPasswordRequest, NullResponse)
'Usage
Dim instance As UserResetPasswordRequestHandler
```

``` csharp
public sealed class UserResetPasswordRequestHandler : WorkflowRequestHandler<UserResetPasswordRequest, NullResponse>
```

``` c++
public ref class UserResetPasswordRequestHandler sealed : public WorkflowRequestHandler<UserResetPasswordRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[UserResetPasswordRequest](userresetpasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.UserResetPasswordRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

