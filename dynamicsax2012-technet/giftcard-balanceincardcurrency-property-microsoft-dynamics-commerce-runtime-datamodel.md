---
title: GiftCard.BalanceInCardCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BalanceInCardCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard.BalanceInCardCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.giftcard.balanceincardcurrency(v=AX.60)
ms:contentKeyID: 62209591
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard.BalanceInCardCurrency
dev_langs:
- CSharp
- C++
- VB
---

# BalanceInCardCurrency Property

Gets or sets the card balance in card's currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BALANCEINCARDCURRENCY")> _
<DataMemberAttribute> _
Public Property BalanceInCardCurrency As Decimal
    Get
    Set
'Usage
Dim instance As GiftCard
Dim value As Decimal

value = instance.BalanceInCardCurrency

instance.BalanceInCardCurrency = value
```

``` csharp
[ColumnAttribute("BALANCEINCARDCURRENCY")]
[DataMemberAttribute]
public decimal BalanceInCardCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"BALANCEINCARDCURRENCY")]
[DataMemberAttribute]
public:
property Decimal BalanceInCardCurrency {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[GiftCard Class](giftcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

