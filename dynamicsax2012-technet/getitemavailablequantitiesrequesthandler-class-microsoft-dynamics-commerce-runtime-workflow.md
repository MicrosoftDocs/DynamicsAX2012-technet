---
title: GetItemAvailableQuantitiesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetItemAvailableQuantitiesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemAvailableQuantitiesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getitemavailablequantitiesrequesthandler(v=AX.60)
ms:contentKeyID: 49855973
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemAvailableQuantitiesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailableQuantitiesRequestHandler Class

Encapsulates the workflow required to get item available quantities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetItemAvailableQuantitiesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetItemAvailableQuantitiesRequest, GetItemAvailableQuantitiesResponse)
'Usage
Dim instance As GetItemAvailableQuantitiesRequestHandler
```

``` csharp
public sealed class GetItemAvailableQuantitiesRequestHandler : WorkflowRequestHandler<GetItemAvailableQuantitiesRequest, GetItemAvailableQuantitiesResponse>
```

``` c++
public ref class GetItemAvailableQuantitiesRequestHandler sealed : public WorkflowRequestHandler<GetItemAvailableQuantitiesRequest^, GetItemAvailableQuantitiesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetItemAvailableQuantitiesRequest](getitemavailablequantitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetItemAvailableQuantitiesResponse](getitemavailablequantitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemAvailableQuantitiesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

