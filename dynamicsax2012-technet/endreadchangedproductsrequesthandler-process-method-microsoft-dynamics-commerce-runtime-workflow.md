---
title: EndReadChangedProductsRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EndReadChangedProductsRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.EndReadChangedProductsRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.endreadchangedproductsrequesthandler.process(v=AX.60)
ms:contentKeyID: 62210505
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EndReadChangedProductsRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow to end the products read session.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As EndReadChangedProductsRequest _
) As EndReadChangedProductsResponse
'Usage
Dim request As EndReadChangedProductsRequest
Dim returnValue As EndReadChangedProductsResponse

returnValue = Me.Process(request)
```

``` csharp
protected override EndReadChangedProductsResponse Process(
    EndReadChangedProductsRequest request
)
```

``` c++
protected:
virtual EndReadChangedProductsResponse^ Process(
    EndReadChangedProductsRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.EndReadChangedProductsRequest](endreadchangedproductsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.EndReadChangedProductsResponse](endreadchangedproductsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[EndReadChangedProductsRequestHandler Class](endreadchangedproductsrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

