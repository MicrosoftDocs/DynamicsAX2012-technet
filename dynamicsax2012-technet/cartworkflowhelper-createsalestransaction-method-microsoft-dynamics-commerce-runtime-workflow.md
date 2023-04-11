---
title: CartWorkflowHelper.CreateSalesTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CreateSalesTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.CreateSalesTransaction(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.createsalestransaction(v=AX.60)
ms:contentKeyID: 62213343
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.CreateSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# CreateSalesTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a sales transaction with given transaction id and customer id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateSalesTransaction ( _
    context As RequestContext, _
    transactionId As String, _
    customerId As String _
) As SalesTransaction
'Usage
Dim context As RequestContext
Dim transactionId As String
Dim customerId As String
Dim returnValue As SalesTransaction

returnValue = CartWorkflowHelper.CreateSalesTransaction(context, _
    transactionId, customerId)
```

``` csharp
public static SalesTransaction CreateSalesTransaction(
    RequestContext context,
    string transactionId,
    string customerId
)
```

``` c++
public:
static SalesTransaction^ CreateSalesTransaction(
    RequestContext^ context, 
    String^ transactionId, 
    String^ customerId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The newly created sales transaction.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

