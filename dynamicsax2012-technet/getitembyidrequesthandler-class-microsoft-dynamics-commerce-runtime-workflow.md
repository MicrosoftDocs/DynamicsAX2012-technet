---
title: GetItemByIdRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetItemByIdRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemByIdRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getitembyidrequesthandler(v=AX.60)
ms:contentKeyID: 49826297
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemByIdRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetItemByIdRequestHandler Class

Encapsulates the workflow required to retrieve an item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetItemByIdRequestHandler _
    Inherits WorkflowRequestHandler(Of GetItemByIdRequest, GetItemByIdResponse)
'Usage
Dim instance As GetItemByIdRequestHandler
```

``` csharp
public sealed class GetItemByIdRequestHandler : WorkflowRequestHandler<GetItemByIdRequest, GetItemByIdResponse>
```

``` c++
public ref class GetItemByIdRequestHandler sealed : public WorkflowRequestHandler<GetItemByIdRequest^, GetItemByIdResponse^>
```

## Remarks

If both ItemId and RecordId have been specified, ItemId takes precedence.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetItemByIdRequest](getitembyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetItemByIdResponse](getitembyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemByIdRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

