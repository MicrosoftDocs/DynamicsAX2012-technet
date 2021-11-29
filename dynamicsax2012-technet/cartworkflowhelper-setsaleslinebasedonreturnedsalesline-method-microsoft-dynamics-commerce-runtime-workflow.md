---
title: CartWorkflowHelper.SetSalesLineBasedOnReturnedSalesLine Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SetSalesLineBasedOnReturnedSalesLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SetSalesLineBasedOnReturnedSalesLine(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.setsaleslinebasedonreturnedsalesline(v=AX.60)
ms:contentKeyID: 62206935
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SetSalesLineBasedOnReturnedSalesLine
dev_langs:
- CSharp
- C++
- VB
---

# SetSalesLineBasedOnReturnedSalesLine Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sets the sales line based on returned sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SetSalesLineBasedOnReturnedSalesLine ( _
    salesLine As SalesLine, _
    returnedSalesLine As SalesLine, _
    returnTransactionId As String, _
    quantity As Decimal _
)
'Usage
Dim salesLine As SalesLine
Dim returnedSalesLine As SalesLine
Dim returnTransactionId As String
Dim quantity As Decimal

CartWorkflowHelper.SetSalesLineBasedOnReturnedSalesLine(salesLine, _
    returnedSalesLine, returnTransactionId, _
    quantity)
```

``` csharp
public static void SetSalesLineBasedOnReturnedSalesLine(
    SalesLine salesLine,
    SalesLine returnedSalesLine,
    string returnTransactionId,
    decimal quantity
)
```

``` c++
public:
static void SetSalesLineBasedOnReturnedSalesLine(
    SalesLine^ salesLine, 
    SalesLine^ returnedSalesLine, 
    String^ returnTransactionId, 
    Decimal quantity
)
```

#### Parameters

  - salesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - returnedSalesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - returnTransactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

