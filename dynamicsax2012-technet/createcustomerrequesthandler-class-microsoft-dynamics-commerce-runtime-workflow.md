---
title: CreateCustomerRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CreateCustomerRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateCustomerRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.createcustomerrequesthandler(v=AX.60)
ms:contentKeyID: 49847834
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateCustomerRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomerRequestHandler Class

CreateCustomerRequest class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CreateCustomerRequestHandler _
    Inherits WorkflowRequestHandler(Of CreateCustomerRequest, CreateCustomerResponse)
'Usage
Dim instance As CreateCustomerRequestHandler
```

``` csharp
public sealed class CreateCustomerRequestHandler : WorkflowRequestHandler<CreateCustomerRequest, CreateCustomerResponse>
```

``` c++
public ref class CreateCustomerRequestHandler sealed : public WorkflowRequestHandler<CreateCustomerRequest^, CreateCustomerResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[CreateCustomerRequest](createcustomerrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [CreateCustomerResponse](createcustomerresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateCustomerRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

