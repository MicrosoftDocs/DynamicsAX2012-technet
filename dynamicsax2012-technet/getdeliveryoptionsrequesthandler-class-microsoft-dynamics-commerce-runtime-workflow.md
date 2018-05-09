---
title: GetDeliveryOptionsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetDeliveryOptionsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeliveryOptionsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getdeliveryoptionsrequesthandler(v=AX.60)
ms:contentKeyID: 49851405
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeliveryOptionsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryOptionsRequestHandler Class

Handles workflow for GetDeliveryOptions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetDeliveryOptionsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetDeliveryOptionsRequest, GetDeliveryOptionsResponse)
'Usage
Dim instance As GetDeliveryOptionsRequestHandler
```

``` csharp
public sealed class GetDeliveryOptionsRequestHandler : WorkflowRequestHandler<GetDeliveryOptionsRequest, GetDeliveryOptionsResponse>
```

``` c++
public ref class GetDeliveryOptionsRequestHandler sealed : public WorkflowRequestHandler<GetDeliveryOptionsRequest^, GetDeliveryOptionsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetDeliveryOptionsRequest](getdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetDeliveryOptionsResponse](getdeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeliveryOptionsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

