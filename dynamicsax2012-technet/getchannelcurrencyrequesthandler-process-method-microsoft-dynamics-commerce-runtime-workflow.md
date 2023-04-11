---
title: GetChannelCurrencyRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelCurrencyRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getchannelcurrencyrequesthandler.process(v=AX.60)
ms:contentKeyID: 62210700
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelCurrencyRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow associated with retrieving list of supported channel currencies.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetChannelCurrencyAmountRequest _
) As GetChannelCurrencyAmountResponse
'Usage
Dim request As GetChannelCurrencyAmountRequest
Dim returnValue As GetChannelCurrencyAmountResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetChannelCurrencyAmountResponse Process(
    GetChannelCurrencyAmountRequest request
)
```

``` c++
protected:
virtual GetChannelCurrencyAmountResponse^ Process(
    GetChannelCurrencyAmountRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountRequest](getchannelcurrencyamountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountResponse](getchannelcurrencyamountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetChannelCurrencyRequestHandler Class](getchannelcurrencyrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

