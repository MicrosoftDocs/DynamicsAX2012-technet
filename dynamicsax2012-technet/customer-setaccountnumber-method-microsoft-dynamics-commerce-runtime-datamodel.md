---
title: Customer.SetAccountNumber Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetAccountNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.SetAccountNumber(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.setaccountnumber(v=AX.60)
ms:contentKeyID: 62210342
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.SetAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# SetAccountNumber Method

Sets the account number if it has not already been set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetAccountNumber ( _
    accountNumber As String _
)
'Usage
Dim instance As Customer
Dim accountNumber As String

instance.SetAccountNumber(accountNumber)
```

``` csharp
public void SetAccountNumber(
    string accountNumber
)
```

``` c++
public:
void SetAccountNumber(
    String^ accountNumber
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## Remarks

This should be used only in special cases. Currently is used only by the pricing engine for discount calculation.

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

