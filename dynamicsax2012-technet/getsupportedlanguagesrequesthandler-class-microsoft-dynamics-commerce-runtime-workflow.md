---
title: GetSupportedLanguagesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetSupportedLanguagesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedLanguagesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getsupportedlanguagesrequesthandler(v=AX.60)
ms:contentKeyID: 62209107
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedLanguagesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetSupportedLanguagesRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve supported languages.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetSupportedLanguagesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetSupportedLanguagesRequest, GetSupportedLanguagesResponse)
'Usage
Dim instance As GetSupportedLanguagesRequestHandler
```

``` csharp
public class GetSupportedLanguagesRequestHandler : WorkflowRequestHandler<GetSupportedLanguagesRequest, GetSupportedLanguagesResponse>
```

``` c++
public ref class GetSupportedLanguagesRequestHandler : public WorkflowRequestHandler<GetSupportedLanguagesRequest^, GetSupportedLanguagesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetSupportedLanguagesRequest](getsupportedlanguagesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetSupportedLanguagesResponse](getsupportedlanguagesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedLanguagesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

