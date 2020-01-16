---
title: GetSupportedLanguagesRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedLanguagesRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedLanguagesRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getsupportedlanguagesrequesthandler.process(v=AX.60)
ms:contentKeyID: 62212466
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedLanguagesRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Executes the workflow associated with retrieving list of supported languages.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetSupportedLanguagesRequest _
) As GetSupportedLanguagesResponse
'Usage
Dim request As GetSupportedLanguagesRequest
Dim returnValue As GetSupportedLanguagesResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetSupportedLanguagesResponse Process(
    GetSupportedLanguagesRequest request
)
```

``` c++
protected:
virtual GetSupportedLanguagesResponse^ Process(
    GetSupportedLanguagesRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedLanguagesRequest](getsupportedlanguagesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedLanguagesResponse](getsupportedlanguagesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetSupportedLanguagesRequestHandler Class](getsupportedlanguagesrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

