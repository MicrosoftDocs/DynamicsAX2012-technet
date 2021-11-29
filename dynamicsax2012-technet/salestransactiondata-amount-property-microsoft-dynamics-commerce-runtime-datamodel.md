---
title: SalesTransactionData.Amount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Amount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.Amount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata.amount(v=AX.60)
ms:contentKeyID: 62212789
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.Amount
dev_langs:
- CSharp
- C++
- VB
---

# Amount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total amount of transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AMOUNT")> _
<IgnoreDataMemberAttribute> _
Public Property Amount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransactionData
Dim value As Decimal

value = instance.Amount

instance.Amount = value
```

``` csharp
[ColumnAttribute("AMOUNT")]
[IgnoreDataMemberAttribute]
public decimal Amount { get; set; }
```

``` c++
[ColumnAttribute(L"AMOUNT")]
[IgnoreDataMemberAttribute]
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

[SalesTransactionData Class](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

