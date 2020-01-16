---
title: GetAvailableStoresRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetAvailableStoresRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableStoresRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getavailablestoresrequesthandler(v=AX.60)
ms:contentKeyID: 62214219
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableStoresRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetAvailableStoresRequestHandler Class

Encapsulates the workflow required to get available stores for device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetAvailableStoresRequestHandler _
    Inherits WorkflowRequestHandler(Of GetAvailableStoresRequest, GetAvailableStoresResponse)
'Usage
Dim instance As GetAvailableStoresRequestHandler
```

``` csharp
public sealed class GetAvailableStoresRequestHandler : WorkflowRequestHandler<GetAvailableStoresRequest, GetAvailableStoresResponse>
```

``` c++
public ref class GetAvailableStoresRequestHandler sealed : public WorkflowRequestHandler<GetAvailableStoresRequest^, GetAvailableStoresResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetAvailableStoresRequest](getavailablestoresrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetAvailableStoresResponse](getavailablestoresresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableStoresRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

