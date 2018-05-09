---
title: UserAuthenticationRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: UserAuthenticationRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.userauthenticationrequesthandler(v=AX.60)
ms:contentKeyID: 62207405
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# UserAuthenticationRequestHandler Class

Encapsulates the workflow required to do user authentication.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class UserAuthenticationRequestHandler _
    Inherits WorkflowRequestHandler(Of UserAuthenticationRequest, UserAuthenticationResponse)
'Usage
Dim instance As UserAuthenticationRequestHandler
```

``` csharp
public sealed class UserAuthenticationRequestHandler : WorkflowRequestHandler<UserAuthenticationRequest, UserAuthenticationResponse>
```

``` c++
public ref class UserAuthenticationRequestHandler sealed : public WorkflowRequestHandler<UserAuthenticationRequest^, UserAuthenticationResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[UserAuthenticationRequest](userauthenticationrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [UserAuthenticationResponse](userauthenticationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

