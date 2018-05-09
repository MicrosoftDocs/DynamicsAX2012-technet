---
title: SalesTransaction.CalculatedDepositAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CalculatedDepositAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CalculatedDepositAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.calculateddepositamount(v=AX.60)
ms:contentKeyID: 62208755
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CalculatedDepositAmount
dev_langs:
- CSharp
- C++
- VB
---

# CalculatedDepositAmount Property

Gets or sets the calculated deposit amount for the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CALCULATEDDEPOSIT")> _
Public Property CalculatedDepositAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.CalculatedDepositAmount

instance.CalculatedDepositAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CALCULATEDDEPOSIT")]
public decimal CalculatedDepositAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CALCULATEDDEPOSIT")]
public:
property Decimal CalculatedDepositAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

