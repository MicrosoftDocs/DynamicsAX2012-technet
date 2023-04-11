---
title: GetChannelProductAttributesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetChannelProductAttributesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelProductAttributesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getchannelproductattributesrequesthandler(v=AX.60)
ms:contentKeyID: 49845346
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelProductAttributesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelProductAttributesRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve the channel product attributes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetChannelProductAttributesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetChannelProductAttributesRequest, GetChannelProductAttributesResponse)
'Usage
Dim instance As GetChannelProductAttributesRequestHandler
```

``` csharp
public sealed class GetChannelProductAttributesRequestHandler : WorkflowRequestHandler<GetChannelProductAttributesRequest, GetChannelProductAttributesResponse>
```

``` c++
public ref class GetChannelProductAttributesRequestHandler sealed : public WorkflowRequestHandler<GetChannelProductAttributesRequest^, GetChannelProductAttributesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetChannelProductAttributesRequest](getchannelproductattributesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetChannelProductAttributesResponse](getchannelproductattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelProductAttributesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

