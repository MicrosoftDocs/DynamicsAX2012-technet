---
title: GetCustomerGroupsRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerGroupsRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerGroupsRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcustomergroupsrequesthandler.process(v=AX.60)
ms:contentKeyID: 62212126
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCustomerGroupsRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow associated with retrieving list of customer groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetCustomerGroupsRequest _
) As GetCustomerGroupsResponse
'Usage
Dim request As GetCustomerGroupsRequest
Dim returnValue As GetCustomerGroupsResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetCustomerGroupsResponse Process(
    GetCustomerGroupsRequest request
)
```

``` c++
protected:
virtual GetCustomerGroupsResponse^ Process(
    GetCustomerGroupsRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerGroupsRequest](getcustomergroupsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerGroupsResponse](getcustomergroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The customer group response.  

## See Also

#### Reference

[GetCustomerGroupsRequestHandler Class](getcustomergroupsrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

