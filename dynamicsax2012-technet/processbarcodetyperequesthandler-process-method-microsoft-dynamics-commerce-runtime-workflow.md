---
title: ProcessBarcodeTypeRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.ProcessBarcodeTypeRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessBarcodeTypeRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.processbarcodetyperequesthandler.process(v=AX.60)
ms:contentKeyID: 62213640
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.ProcessBarcodeTypeRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Executes the workflow to process the incoming barcode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As ProcessBarcodeTypeRequest _
) As ProcessBarcodeTypeResponse
'Usage
Dim request As ProcessBarcodeTypeRequest
Dim returnValue As ProcessBarcodeTypeResponse

returnValue = Me.Process(request)
```

``` csharp
protected override ProcessBarcodeTypeResponse Process(
    ProcessBarcodeTypeRequest request
)
```

``` c++
protected:
virtual ProcessBarcodeTypeResponse^ Process(
    ProcessBarcodeTypeRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessBarcodeTypeRequest](processbarcodetyperequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessBarcodeTypeResponse](processbarcodetyperesponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
Instance of [ProcessBarcodeTypeResponse](processbarcodetyperesponse-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[ProcessBarcodeTypeRequestHandler Class](processbarcodetyperequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

