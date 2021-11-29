---
title: SearchStoreRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.SearchStoreRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.searchstorerequesthandler.process(v=AX.60)
ms:contentKeyID: 62213344
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SearchStoreRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow to retrieve store information using the specified criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As SearchStoreRequest _
) As SearchStoreResponse
'Usage
Dim request As SearchStoreRequest
Dim returnValue As SearchStoreResponse

returnValue = Me.Process(request)
```

``` csharp
protected override SearchStoreResponse Process(
    SearchStoreRequest request
)
```

``` c++
protected:
virtual SearchStoreResponse^ Process(
    SearchStoreRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreRequest](searchstorerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreResponse](searchstoreresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[SearchStoreRequestHandler Class](searchstorerequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

