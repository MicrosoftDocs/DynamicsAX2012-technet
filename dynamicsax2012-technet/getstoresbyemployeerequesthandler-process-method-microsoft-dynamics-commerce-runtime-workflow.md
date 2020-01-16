---
title: GetStoresByEmployeeRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoresByEmployeeRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresByEmployeeRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getstoresbyemployeerequesthandler.process(v=AX.60)
ms:contentKeyID: 62209899
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStoresByEmployeeRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Executes the workflow to get Stores By Employee.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetStoresByEmployeeRequest _
) As GetStoresByEmployeeResponse
'Usage
Dim request As GetStoresByEmployeeRequest
Dim returnValue As GetStoresByEmployeeResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetStoresByEmployeeResponse Process(
    GetStoresByEmployeeRequest request
)
```

``` c++
protected:
virtual GetStoresByEmployeeResponse^ Process(
    GetStoresByEmployeeRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresByEmployeeRequest](getstoresbyemployeerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresByEmployeeResponse](getstoresbyemployeeresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
Instance of [GetStoresByEmployeeResponse](getstoresbyemployeeresponse-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[GetStoresByEmployeeRequestHandler Class](getstoresbyemployeerequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

