---
title: SaveKitTransactionRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveKitTransactionRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.SaveKitTransactionRequest)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.savekittransactionrequesthandler.process(v=AX.60)
ms:contentKeyID: 62215074
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveKitTransactionRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Executes the workflow to save transactions from kit (disassembly) operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As SaveKitTransactionRequest _
) As SaveKitTransactionResponse
'Usage
Dim request As SaveKitTransactionRequest
Dim returnValue As SaveKitTransactionResponse

returnValue = Me.Process(request)
```

``` csharp
protected override SaveKitTransactionResponse Process(
    SaveKitTransactionRequest request
)
```

``` c++
protected:
virtual SaveKitTransactionResponse^ Process(
    SaveKitTransactionRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveKitTransactionRequest](savekittransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveKitTransactionResponse](savekittransactionresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
Instance of [SaveKitTransactionResponse](savekittransactionresponse-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[SaveKitTransactionRequestHandler Class](savekittransactionrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

