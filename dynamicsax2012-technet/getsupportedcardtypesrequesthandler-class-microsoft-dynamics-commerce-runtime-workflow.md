---
title: GetSupportedCardTypesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetSupportedCardTypesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedCardTypesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getsupportedcardtypesrequesthandler(v=AX.60)
ms:contentKeyID: 49826770
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedCardTypesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetSupportedCardTypesRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves list of supported credit cards associated with the channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetSupportedCardTypesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetSupportedCardTypesRequest, GetSupportedCardTypesResponse)
'Usage
Dim instance As GetSupportedCardTypesRequestHandler
```

``` csharp
public sealed class GetSupportedCardTypesRequestHandler : WorkflowRequestHandler<GetSupportedCardTypesRequest, GetSupportedCardTypesResponse>
```

``` c++
public ref class GetSupportedCardTypesRequestHandler sealed : public WorkflowRequestHandler<GetSupportedCardTypesRequest^, GetSupportedCardTypesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetSupportedCardTypesRequest](getsupportedcardtypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetSupportedCardTypesResponse](getsupportedcardtypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedCardTypesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

