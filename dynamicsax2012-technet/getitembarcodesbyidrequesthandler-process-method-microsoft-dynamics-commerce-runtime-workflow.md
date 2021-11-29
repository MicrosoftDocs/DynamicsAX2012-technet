---
title: GetItemBarcodesByIdRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemBarcodesByIdRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getitembarcodesbyidrequesthandler.process(v=AX.60)
ms:contentKeyID: 62206722
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemBarcodesByIdRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets batch of barcodes given list of Item Ids. an offline sales order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetItemBarcodesByIdRequest _
) As GetItemBarcodesByIdResponse
'Usage
Dim request As GetItemBarcodesByIdRequest
Dim returnValue As GetItemBarcodesByIdResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetItemBarcodesByIdResponse Process(
    GetItemBarcodesByIdRequest request
)
```

``` c++
protected:
virtual GetItemBarcodesByIdResponse^ Process(
    GetItemBarcodesByIdRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdRequest](getitembarcodesbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdResponse](getitembarcodesbyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetItemBarcodesByIdRequestHandler Class](getitembarcodesbyidrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

