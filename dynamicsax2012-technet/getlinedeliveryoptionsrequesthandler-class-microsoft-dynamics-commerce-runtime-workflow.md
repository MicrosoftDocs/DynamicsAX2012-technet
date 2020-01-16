---
title: GetLineDeliveryOptionsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetLineDeliveryOptionsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLineDeliveryOptionsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getlinedeliveryoptionsrequesthandler(v=AX.60)
ms:contentKeyID: 62208629
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLineDeliveryOptionsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetLineDeliveryOptionsRequestHandler Class

Handles workflow for GetLineDeliveryOptions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetLineDeliveryOptionsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetLineDeliveryOptionsRequest, GetLineDeliveryOptionsResponse)
'Usage
Dim instance As GetLineDeliveryOptionsRequestHandler
```

``` csharp
public sealed class GetLineDeliveryOptionsRequestHandler : WorkflowRequestHandler<GetLineDeliveryOptionsRequest, GetLineDeliveryOptionsResponse>
```

``` c++
public ref class GetLineDeliveryOptionsRequestHandler sealed : public WorkflowRequestHandler<GetLineDeliveryOptionsRequest^, GetLineDeliveryOptionsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetLineDeliveryOptionsRequest](getlinedeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetLineDeliveryOptionsResponse](getlinedeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLineDeliveryOptionsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

