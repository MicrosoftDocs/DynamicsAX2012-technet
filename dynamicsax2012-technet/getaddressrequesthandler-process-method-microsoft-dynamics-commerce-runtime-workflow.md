---
title: GetAddressRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAddressRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getaddressrequesthandler.process(v=AX.60)
ms:contentKeyID: 62206693
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAddressRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Executes the workflow to fetch the Address information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetAddressRequest _
) As GetAddressResponse
'Usage
Dim request As GetAddressRequest
Dim returnValue As GetAddressResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetAddressResponse Process(
    GetAddressRequest request
)
```

``` c++
protected:
virtual GetAddressResponse^ Process(
    GetAddressRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest](getaddressrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
Instance of [GetAddressResponse](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[GetAddressRequestHandler Class](getaddressrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

