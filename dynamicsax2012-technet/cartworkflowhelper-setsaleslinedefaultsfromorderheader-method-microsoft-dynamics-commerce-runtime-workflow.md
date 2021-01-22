---
title: CartWorkflowHelper.SetSalesLineDefaultsFromOrderHeader Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SetSalesLineDefaultsFromOrderHeader Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SetSalesLineDefaultsFromOrderHeader(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.setsaleslinedefaultsfromorderheader(v=AX.60)
ms:contentKeyID: 62213220
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SetSalesLineDefaultsFromOrderHeader
dev_langs:
- CSharp
- C++
- VB
---

# SetSalesLineDefaultsFromOrderHeader Method

Sets the default properties on the sales line from the order header.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SetSalesLineDefaultsFromOrderHeader ( _
    salesLine As SalesLine, _
    salesTransaction As SalesTransaction _
)
'Usage
Dim salesLine As SalesLine
Dim salesTransaction As SalesTransaction

CartWorkflowHelper.SetSalesLineDefaultsFromOrderHeader(salesLine, _
    salesTransaction)
```

``` csharp
public static void SetSalesLineDefaultsFromOrderHeader(
    SalesLine salesLine,
    SalesTransaction salesTransaction
)
```

``` c++
public:
static void SetSalesLineDefaultsFromOrderHeader(
    SalesLine^ salesLine, 
    SalesTransaction^ salesTransaction
)
```

#### Parameters

  - salesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

