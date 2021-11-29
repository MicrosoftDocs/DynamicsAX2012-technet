---
title: GetCardTypeRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCardTypeRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCardTypeRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcardtyperequesthandler(v=AX.60)
ms:contentKeyID: 62202107
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCardTypeRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCardTypeRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Workflow class helps to retrieve the CardType details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetCardTypeRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCardTypesRequest, GetCardTypesResponse)
'Usage
Dim instance As GetCardTypeRequestHandler
```

``` csharp
public class GetCardTypeRequestHandler : WorkflowRequestHandler<GetCardTypesRequest, GetCardTypesResponse>
```

``` c++
public ref class GetCardTypeRequestHandler : public WorkflowRequestHandler<GetCardTypesRequest^, GetCardTypesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCardTypesRequest](getcardtypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCardTypesResponse](getcardtypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCardTypeRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

