---
title: BeginReadChangedProductsRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.BeginReadChangedProductsRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.BeginReadChangedProductsRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.beginreadchangedproductsrequesthandler.process(v=AX.60)
ms:contentKeyID: 62214742
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.BeginReadChangedProductsRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Executes the workflow to retrieve changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As BeginReadChangedProductsRequest _
) As BeginReadChangedProductsResponse
'Usage
Dim request As BeginReadChangedProductsRequest
Dim returnValue As BeginReadChangedProductsResponse

returnValue = Me.Process(request)
```

``` csharp
protected override BeginReadChangedProductsResponse Process(
    BeginReadChangedProductsRequest request
)
```

``` c++
protected:
virtual BeginReadChangedProductsResponse^ Process(
    BeginReadChangedProductsRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.BeginReadChangedProductsRequest](beginreadchangedproductsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.BeginReadChangedProductsResponse](beginreadchangedproductsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[BeginReadChangedProductsRequestHandler Class](beginreadchangedproductsrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

