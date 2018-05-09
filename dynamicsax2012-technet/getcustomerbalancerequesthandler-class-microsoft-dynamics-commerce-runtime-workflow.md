---
title: GetCustomerBalanceRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCustomerBalanceRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerBalanceRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getcustomerbalancerequesthandler(v=AX.60)
ms:contentKeyID: 62202974
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerBalanceRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerBalanceRequestHandler Class

Get customer balance request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetCustomerBalanceRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCustomerBalanceRequest, GetCustomerBalanceResponse)
'Usage
Dim instance As GetCustomerBalanceRequestHandler
```

``` csharp
public sealed class GetCustomerBalanceRequestHandler : WorkflowRequestHandler<GetCustomerBalanceRequest, GetCustomerBalanceResponse>
```

``` c++
public ref class GetCustomerBalanceRequestHandler sealed : public WorkflowRequestHandler<GetCustomerBalanceRequest^, GetCustomerBalanceResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCustomerBalanceRequest](getcustomerbalancerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCustomerBalanceResponse](getcustomerbalanceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerBalanceRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

