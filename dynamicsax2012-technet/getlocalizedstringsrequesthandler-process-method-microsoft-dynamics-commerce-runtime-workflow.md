---
title: GetLocalizedStringsRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLocalizedStringsRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getlocalizedstringsrequesthandler.process(v=AX.60)
ms:contentKeyID: 62213940
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLocalizedStringsRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow associated with retrieving localized strings, optionally by language and text identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetLocalizedStringsRequest _
) As GetLocalizedStringsResponse
'Usage
Dim request As GetLocalizedStringsRequest
Dim returnValue As GetLocalizedStringsResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetLocalizedStringsResponse Process(
    GetLocalizedStringsRequest request
)
```

``` c++
protected:
virtual GetLocalizedStringsResponse^ Process(
    GetLocalizedStringsRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsRequest](getlocalizedstringsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsResponse](getlocalizedstringsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetLocalizedStringsRequestHandler Class](getlocalizedstringsrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

