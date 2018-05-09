---
title: UserAuthenticationRenewalRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: UserAuthenticationRenewalRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRenewalRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.userauthenticationrenewalrequesthandler(v=AX.60)
ms:contentKeyID: 62206604
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRenewalRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# UserAuthenticationRenewalRequestHandler Class

Encapsulates the workflow required to do user authentication renewal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class UserAuthenticationRenewalRequestHandler _
    Inherits WorkflowRequestHandler(Of UserAuthenticationRenewalRequest, UserAuthenticationRenewalResponse)
'Usage
Dim instance As UserAuthenticationRenewalRequestHandler
```

``` csharp
public sealed class UserAuthenticationRenewalRequestHandler : WorkflowRequestHandler<UserAuthenticationRenewalRequest, UserAuthenticationRenewalResponse>
```

``` c++
public ref class UserAuthenticationRenewalRequestHandler sealed : public WorkflowRequestHandler<UserAuthenticationRenewalRequest^, UserAuthenticationRenewalResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[UserAuthenticationRenewalRequest](userauthenticationrenewalrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [UserAuthenticationRenewalResponse](userauthenticationrenewalresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRenewalRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

