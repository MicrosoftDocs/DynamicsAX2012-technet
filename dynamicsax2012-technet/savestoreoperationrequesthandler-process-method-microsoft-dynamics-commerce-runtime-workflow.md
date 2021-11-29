---
title: SaveStoreOperationRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStoreOperationRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.savestoreoperationrequesthandler.process(v=AX.60)
ms:contentKeyID: 62210314
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStoreOperationRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow to save non-sale transactions from store operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As SaveStoreOperationRequest _
) As SaveStoreOperationResponse
'Usage
Dim request As SaveStoreOperationRequest
Dim returnValue As SaveStoreOperationResponse

returnValue = Me.Process(request)
```

``` csharp
protected override SaveStoreOperationResponse Process(
    SaveStoreOperationRequest request
)
```

``` c++
protected:
virtual SaveStoreOperationResponse^ Process(
    SaveStoreOperationRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationRequest](savestoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationResponse](savestoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
Instance of [SaveStoreOperationResponse](savestoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[SaveStoreOperationRequestHandler Class](savestoreoperationrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

