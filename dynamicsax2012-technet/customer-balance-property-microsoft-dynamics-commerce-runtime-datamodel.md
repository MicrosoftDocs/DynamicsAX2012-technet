---
title: Customer.Balance Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Balance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Balance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.balance(v=AX.60)
ms:contentKeyID: 62211991
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Balance
dev_langs:
- CSharp
- C++
- VB
---

# Balance Property

Gets or sets the balance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BALANCE")> _
<DataMemberAttribute> _
Public Property Balance As Decimal
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Decimal

value = instance.Balance

instance.Balance = value
```

``` csharp
[ColumnAttribute("BALANCE")]
[DataMemberAttribute]
public decimal Balance { get; set; }
```

``` c++
[ColumnAttribute(L"BALANCE")]
[DataMemberAttribute]
public:
property Decimal Balance {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The balance.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

