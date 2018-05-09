---
title: ICustomerV1.TransactionsReport Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TransactionsReport Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.TransactionsReport(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.transactionsreport(v=AX.60)
ms:contentKeyID: 47344490
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.TransactionsReport
dev_langs:
- CSharp
- C++
- VB
---

# TransactionsReport Method

Prints customer transactions for customer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub TransactionsReport ( _
    customerId As String _
)
'Usage
Dim instance As ICustomerV1
Dim customerId As String

instance.TransactionsReport(customerId)
```

``` csharp
void TransactionsReport(
    string customerId
)
```

``` c++
void TransactionsReport(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## Remarks

This method is triggered by the customer transaction report operation.

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

