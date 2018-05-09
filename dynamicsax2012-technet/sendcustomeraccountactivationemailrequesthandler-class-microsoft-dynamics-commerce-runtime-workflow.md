---
title: SendCustomerAccountActivationEmailRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SendCustomerAccountActivationEmailRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SendCustomerAccountActivationEmailRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.sendcustomeraccountactivationemailrequesthandler(v=AX.60)
ms:contentKeyID: 62214123
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SendCustomerAccountActivationEmailRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SendCustomerAccountActivationEmailRequestHandler Class

Encapsulates the workflow to send an e-mail to a specified user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SendCustomerAccountActivationEmailRequestHandler _
    Inherits WorkflowRequestHandler(Of SendCustomerAccountActivationEmailRequest, NullResponse)
'Usage
Dim instance As SendCustomerAccountActivationEmailRequestHandler
```

``` csharp
public sealed class SendCustomerAccountActivationEmailRequestHandler : WorkflowRequestHandler<SendCustomerAccountActivationEmailRequest, NullResponse>
```

``` c++
public ref class SendCustomerAccountActivationEmailRequestHandler sealed : public WorkflowRequestHandler<SendCustomerAccountActivationEmailRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SendCustomerAccountActivationEmailRequest](sendcustomeraccountactivationemailrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SendCustomerAccountActivationEmailRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

