---
title: CartWorkflowHelper.GetSalesLineByNumber Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetSalesLineByNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetSalesLineByNumber(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.getsaleslinebynumber(v=AX.60)
ms:contentKeyID: 62210888
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetSalesLineByNumber
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesLineByNumber Method

The a sales line from the sales transaction by the line number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetSalesLineByNumber ( _
    salesTransaction As SalesTransaction, _
    lineNumber As Decimal _
) As SalesLine
'Usage
Dim salesTransaction As SalesTransaction
Dim lineNumber As Decimal
Dim returnValue As SalesLine

returnValue = CartWorkflowHelper.GetSalesLineByNumber(salesTransaction, _
    lineNumber)
```

``` csharp
public static SalesLine GetSalesLineByNumber(
    SalesTransaction salesTransaction,
    decimal lineNumber
)
```

``` c++
public:
static SalesLine^ GetSalesLineByNumber(
    SalesTransaction^ salesTransaction, 
    Decimal lineNumber
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - lineNumber  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales line.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

