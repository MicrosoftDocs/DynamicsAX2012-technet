---
title: SalesTransaction.RequiredDepositAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RequiredDepositAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.RequiredDepositAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.requireddepositamount(v=AX.60)
ms:contentKeyID: 62213465
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.RequiredDepositAmount
dev_langs:
- CSharp
- C++
- VB
---

# RequiredDepositAmount Property

Gets or sets the required deposit amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REQUIREDDEPOSIT")> _
Public Property RequiredDepositAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.RequiredDepositAmount

instance.RequiredDepositAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REQUIREDDEPOSIT")]
public decimal RequiredDepositAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REQUIREDDEPOSIT")]
public:
property Decimal RequiredDepositAmount {
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

