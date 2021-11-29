---
title: GetCommerceListRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCommerceListRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCommerceListRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcommercelistrequesthandler(v=AX.60)
ms:contentKeyID: 62208689
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCommerceListRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCommerceListRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the commerce lists specified by the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetCommerceListRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCommerceListRequest, GetCommerceListResponse)
'Usage
Dim instance As GetCommerceListRequestHandler
```

``` csharp
public sealed class GetCommerceListRequestHandler : WorkflowRequestHandler<GetCommerceListRequest, GetCommerceListResponse>
```

``` c++
public ref class GetCommerceListRequestHandler sealed : public WorkflowRequestHandler<GetCommerceListRequest^, GetCommerceListResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCommerceListRequest](getcommercelistrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCommerceListResponse](getcommercelistresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCommerceListRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

