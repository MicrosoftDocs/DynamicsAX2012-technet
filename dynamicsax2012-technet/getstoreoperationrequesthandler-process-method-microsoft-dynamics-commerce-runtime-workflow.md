---
title: GetStoreOperationRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoreOperationRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getstoreoperationrequesthandler.process(v=AX.60)
ms:contentKeyID: 62212416
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoreOperationRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Executes the workflow to get aggregated value of drawer entry operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetStoreOperationRequest _
) As GetStoreOperationResponse
'Usage
Dim request As GetStoreOperationRequest
Dim returnValue As GetStoreOperationResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetStoreOperationResponse Process(
    GetStoreOperationRequest request
)
```

``` c++
protected:
virtual GetStoreOperationResponse^ Process(
    GetStoreOperationRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationRequest](getstoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationResponse](getstoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
Instance of [GetStoreOperationResponse](getstoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[GetStoreOperationRequestHandler Class](getstoreoperationrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

