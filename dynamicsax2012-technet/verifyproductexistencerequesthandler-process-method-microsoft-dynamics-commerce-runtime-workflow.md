---
title: VerifyProductExistenceRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.VerifyProductExistenceRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.verifyproductexistencerequesthandler.process(v=AX.60)
ms:contentKeyID: 62209738
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.VerifyProductExistenceRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow to retrieve changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As VerifyProductExistenceRequest _
) As VerifyProductExistenceResponse
'Usage
Dim request As VerifyProductExistenceRequest
Dim returnValue As VerifyProductExistenceResponse

returnValue = Me.Process(request)
```

``` csharp
protected override VerifyProductExistenceResponse Process(
    VerifyProductExistenceRequest request
)
```

``` c++
protected:
virtual VerifyProductExistenceResponse^ Process(
    VerifyProductExistenceRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceRequest](verifyproductexistencerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceResponse](verifyproductexistenceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[VerifyProductExistenceRequestHandler Class](verifyproductexistencerequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

