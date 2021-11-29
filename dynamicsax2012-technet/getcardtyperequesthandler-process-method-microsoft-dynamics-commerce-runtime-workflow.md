---
title: GetCardTypeRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCardTypeRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcardtyperequesthandler.process(v=AX.60)
ms:contentKeyID: 62211527
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCardTypeRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

CardType workflow handler to process the incoming workflow requests.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetCardTypesRequest _
) As GetCardTypesResponse
'Usage
Dim request As GetCardTypesRequest
Dim returnValue As GetCardTypesResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetCardTypesResponse Process(
    GetCardTypesRequest request
)
```

``` c++
protected:
virtual GetCardTypesResponse^ Process(
    GetCardTypesRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesRequest](getcardtypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesResponse](getcardtypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
Returns GetCardTypesResponse response object.  

## See Also

#### Reference

[GetCardTypeRequestHandler Class](getcardtyperequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

