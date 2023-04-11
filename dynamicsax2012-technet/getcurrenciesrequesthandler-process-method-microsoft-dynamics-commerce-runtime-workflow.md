---
title: GetCurrenciesRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrenciesRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrenciesRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcurrenciesrequesthandler.process(v=AX.60)
ms:contentKeyID: 62214204
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrenciesRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow associated with retrieving list of currencies.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetCurrenciesRequest _
) As GetCurrenciesResponse
'Usage
Dim request As GetCurrenciesRequest
Dim returnValue As GetCurrenciesResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetCurrenciesResponse Process(
    GetCurrenciesRequest request
)
```

``` c++
protected:
virtual GetCurrenciesResponse^ Process(
    GetCurrenciesRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrenciesRequest](getcurrenciesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrenciesResponse](getcurrenciesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetCurrenciesRequestHandler Class](getcurrenciesrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

