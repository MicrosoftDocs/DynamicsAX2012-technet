---
title: GetBarcodeRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetBarcodeRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetBarcodeRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getbarcoderequesthandler.process(v=AX.60)
ms:contentKeyID: 62210087
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetBarcodeRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Barcode workflow handler to process the incoming workflow requests.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetBarcodeRequest _
) As GetBarcodeResponse
'Usage
Dim request As GetBarcodeRequest
Dim returnValue As GetBarcodeResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetBarcodeResponse Process(
    GetBarcodeRequest request
)
```

``` c++
protected:
virtual GetBarcodeResponse^ Process(
    GetBarcodeRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetBarcodeRequest](getbarcoderequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetBarcodeResponse](getbarcoderesponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
GetBarcodeResponse object.  

## See Also

#### Reference

[GetBarcodeRequestHandler Class](getbarcoderequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

