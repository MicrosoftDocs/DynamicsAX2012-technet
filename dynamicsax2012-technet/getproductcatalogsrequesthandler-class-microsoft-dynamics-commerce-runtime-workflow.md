---
title: GetProductCatalogsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetProductCatalogsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductCatalogsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getproductcatalogsrequesthandler(v=AX.60)
ms:contentKeyID: 62209640
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductCatalogsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetProductCatalogsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves the collection of product catalogs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetProductCatalogsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetProductCatalogsRequest, GetProductCatalogsResponse)
'Usage
Dim instance As GetProductCatalogsRequestHandler
```

``` csharp
public sealed class GetProductCatalogsRequestHandler : WorkflowRequestHandler<GetProductCatalogsRequest, GetProductCatalogsResponse>
```

``` c++
public ref class GetProductCatalogsRequestHandler sealed : public WorkflowRequestHandler<GetProductCatalogsRequest^, GetProductCatalogsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetProductCatalogsRequest](getproductcatalogsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetProductCatalogsResponse](getproductcatalogsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductCatalogsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

