---
title: CustomerSearchRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CustomerSearchRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerSearchRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customersearchrequesthandler(v=AX.60)
ms:contentKeyID: 62207994
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerSearchRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# CustomerSearchRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Customer search request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CustomerSearchRequestHandler _
    Inherits WorkflowRequestHandler(Of CustomersSearchRequest, CustomersSearchResponse)
'Usage
Dim instance As CustomerSearchRequestHandler
```

``` csharp
public sealed class CustomerSearchRequestHandler : WorkflowRequestHandler<CustomersSearchRequest, CustomersSearchResponse>
```

``` c++
public ref class CustomerSearchRequestHandler sealed : public WorkflowRequestHandler<CustomersSearchRequest^, CustomersSearchResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[CustomersSearchRequest](customerssearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [CustomersSearchResponse](customerssearchresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerSearchRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

