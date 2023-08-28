---
title: GetAddressRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetAddressRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAddressRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getaddressrequesthandler(v=AX.60)
ms:contentKeyID: 62212659
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAddressRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetAddressRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the global address values that consists of countries/regions, counties, state provinces, cities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetAddressRequestHandler _
    Inherits WorkflowRequestHandler(Of GetAddressRequest, GetAddressResponse)
'Usage
Dim instance As GetAddressRequestHandler
```

``` csharp
public class GetAddressRequestHandler : WorkflowRequestHandler<GetAddressRequest, GetAddressResponse>
```

``` c++
public ref class GetAddressRequestHandler : public WorkflowRequestHandler<GetAddressRequest^, GetAddressResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetAddressRequest](getaddressrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetAddressResponse](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAddressRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

