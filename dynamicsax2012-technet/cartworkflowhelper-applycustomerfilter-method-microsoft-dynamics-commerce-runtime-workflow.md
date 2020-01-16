---
title: CartWorkflowHelper.ApplyCustomerFilter Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ApplyCustomerFilter Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ApplyCustomerFilter(System.String,System.Boolean,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.applycustomerfilter(v=AX.60)
ms:contentKeyID: 65319523
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ApplyCustomerFilter
dev_langs:
- CSharp
- C++
- VB
---

# ApplyCustomerFilter Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ApplyCustomerFilter ( _
    customerId As String, _
    filterByCustomer As Boolean, _
    salesTransactions As IEnumerable(Of SalesTransaction) _
) As IEnumerable(Of SalesTransaction)
'Usage
Dim customerId As String
Dim filterByCustomer As Boolean
Dim salesTransactions As IEnumerable(Of SalesTransaction)
Dim returnValue As IEnumerable(Of SalesTransaction)

returnValue = CartWorkflowHelper.ApplyCustomerFilter(customerId, _
    filterByCustomer, salesTransactions)
```

``` csharp
public static IEnumerable<SalesTransaction> ApplyCustomerFilter(
    string customerId,
    bool filterByCustomer,
    IEnumerable<SalesTransaction> salesTransactions
)
```

``` c++
public:
static IEnumerable<SalesTransaction^>^ ApplyCustomerFilter(
    String^ customerId, 
    bool filterByCustomer, 
    IEnumerable<SalesTransaction^>^ salesTransactions
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - filterByCustomer  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - salesTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

