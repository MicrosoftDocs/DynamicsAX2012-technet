---
title: CartWorkflowHelper.LoadSalesTransactionsByCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: LoadSalesTransactionsByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LoadSalesTransactionsByCustomer(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.loadsalestransactionsbycustomer(v=AX.60)
ms:contentKeyID: 62211240
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LoadSalesTransactionsByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# LoadSalesTransactionsByCustomer Method

Loads the sales transactions given the customer identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function LoadSalesTransactionsByCustomer ( _
    context As RequestContext, _
    customerId As String _
) As IEnumerable(Of SalesTransaction)
'Usage
Dim context As RequestContext
Dim customerId As String
Dim returnValue As IEnumerable(Of SalesTransaction)

returnValue = CartWorkflowHelper.LoadSalesTransactionsByCustomer(context, _
    customerId)
```

``` csharp
public static IEnumerable<SalesTransaction> LoadSalesTransactionsByCustomer(
    RequestContext context,
    string customerId
)
```

``` c++
public:
static IEnumerable<SalesTransaction^>^ LoadSalesTransactionsByCustomer(
    RequestContext^ context, 
    String^ customerId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The loaded sales transaction.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

