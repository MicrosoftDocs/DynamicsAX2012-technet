---
title: GetAllStoreEmployeesRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAllStoreEmployeesRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllStoreEmployeesRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getallstoreemployeesrequesthandler.process(v=AX.60)
ms:contentKeyID: 62214596
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAllStoreEmployeesRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow to get available stores.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetAllStoreEmployeesRequest _
) As GetAllStoreEmployeesResponse
'Usage
Dim request As GetAllStoreEmployeesRequest
Dim returnValue As GetAllStoreEmployeesResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetAllStoreEmployeesResponse Process(
    GetAllStoreEmployeesRequest request
)
```

``` c++
protected:
virtual GetAllStoreEmployeesResponse^ Process(
    GetAllStoreEmployeesRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllStoreEmployeesRequest](getallstoreemployeesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllStoreEmployeesResponse](getallstoreemployeesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetAllStoreEmployeesRequestHandler Class](getallstoreemployeesrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

