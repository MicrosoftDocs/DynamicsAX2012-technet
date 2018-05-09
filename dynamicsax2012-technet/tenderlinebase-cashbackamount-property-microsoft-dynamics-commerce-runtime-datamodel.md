---
title: TenderLineBase.CashBackAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CashBackAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CashBackAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.cashbackamount(v=AX.60)
ms:contentKeyID: 62211312
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CashBackAmount
dev_langs:
- CSharp
- C++
- VB
---

# CashBackAmount Property

Gets or sets the cashback amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CASHBACKAMOUNT")> _
Public Property CashBackAmount As Decimal
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Decimal

value = instance.CashBackAmount

instance.CashBackAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CASHBACKAMOUNT")]
public decimal CashBackAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CASHBACKAMOUNT")]
public:
property Decimal CashBackAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The cashback amount.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

