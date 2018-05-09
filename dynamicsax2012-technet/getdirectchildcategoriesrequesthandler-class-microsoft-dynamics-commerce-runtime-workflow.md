---
title: GetDirectChildCategoriesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetDirectChildCategoriesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDirectChildCategoriesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getdirectchildcategoriesrequesthandler(v=AX.60)
ms:contentKeyID: 62211811
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDirectChildCategoriesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetDirectChildCategoriesRequestHandler Class

Handles workflow for GetDirectChildCategoriesRequest.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetDirectChildCategoriesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetDirectChildCategoriesRequest, GetChannelCategoryHierarchyResponse)
'Usage
Dim instance As GetDirectChildCategoriesRequestHandler
```

``` csharp
public sealed class GetDirectChildCategoriesRequestHandler : WorkflowRequestHandler<GetDirectChildCategoriesRequest, GetChannelCategoryHierarchyResponse>
```

``` c++
public ref class GetDirectChildCategoriesRequestHandler sealed : public WorkflowRequestHandler<GetDirectChildCategoriesRequest^, GetChannelCategoryHierarchyResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetDirectChildCategoriesRequest](getdirectchildcategoriesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetChannelCategoryHierarchyResponse](getchannelcategoryhierarchyresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDirectChildCategoriesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

