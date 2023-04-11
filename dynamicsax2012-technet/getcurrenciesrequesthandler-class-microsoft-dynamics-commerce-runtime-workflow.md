---
title: GetCurrenciesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCurrenciesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrenciesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcurrenciesrequesthandler(v=AX.60)
ms:contentKeyID: 62213368
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrenciesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrenciesRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve currencies.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetCurrenciesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCurrenciesRequest, GetCurrenciesResponse)
'Usage
Dim instance As GetCurrenciesRequestHandler
```

``` csharp
public class GetCurrenciesRequestHandler : WorkflowRequestHandler<GetCurrenciesRequest, GetCurrenciesResponse>
```

``` c++
public ref class GetCurrenciesRequestHandler : public WorkflowRequestHandler<GetCurrenciesRequest^, GetCurrenciesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCurrenciesRequest](getcurrenciesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCurrenciesResponse](getcurrenciesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrenciesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

