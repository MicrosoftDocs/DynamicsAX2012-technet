---
title: NonSalesTransaction.Amount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Amount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.Amount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.nonsalestransaction.amount(v=AX.60)
ms:contentKeyID: 62206235
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.Amount
dev_langs:
- CSharp
- C++
- VB
---

# Amount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the amount of the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AMOUNT")> _
Public Property Amount As Decimal
    Get
    Set
'Usage
Dim instance As NonSalesTransaction
Dim value As Decimal

value = instance.Amount

instance.Amount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AMOUNT")]
public decimal Amount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AMOUNT")]
public:
property Decimal Amount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[NonSalesTransaction Class](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

