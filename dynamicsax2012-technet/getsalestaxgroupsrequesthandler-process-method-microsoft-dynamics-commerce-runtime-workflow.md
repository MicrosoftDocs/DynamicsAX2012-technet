---
title: GetSalesTaxGroupsRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSalesTaxGroupsRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetSalesTaxGroupsRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getsalestaxgroupsrequesthandler.process(v=AX.60)
ms:contentKeyID: 62210404
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSalesTaxGroupsRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Executes the workflow associated with retrieving list of sales tax groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetSalesTaxGroupsRequest _
) As GetSalesTaxGroupsResponse
'Usage
Dim request As GetSalesTaxGroupsRequest
Dim returnValue As GetSalesTaxGroupsResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetSalesTaxGroupsResponse Process(
    GetSalesTaxGroupsRequest request
)
```

``` c++
protected:
virtual GetSalesTaxGroupsResponse^ Process(
    GetSalesTaxGroupsRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetSalesTaxGroupsRequest](getsalestaxgroupsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetSalesTaxGroupsResponse](getsalestaxgroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetSalesTaxGroupsRequestHandler Class](getsalestaxgroupsrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

