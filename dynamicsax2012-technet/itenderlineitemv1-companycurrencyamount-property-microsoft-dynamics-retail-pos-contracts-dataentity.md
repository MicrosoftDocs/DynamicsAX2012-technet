---
title: ITenderLineItemV1.CompanyCurrencyAmount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CompanyCurrencyAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.CompanyCurrencyAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderlineitemv1.companycurrencyamount(v=AX.60)
ms:contentKeyID: 49826708
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.CompanyCurrencyAmount
dev_langs:
- CSharp
- C++
- VB
---

# CompanyCurrencyAmount Property

The Company exchange amount used at the Head Office (as retrieved from the companyinfo table).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CompanyCurrencyAmount As Decimal
    Get
    Set
'Usage
Dim instance As ITenderLineItemV1
Dim value As Decimal

value = instance.CompanyCurrencyAmount

instance.CompanyCurrencyAmount = value
```

``` csharp
decimal CompanyCurrencyAmount { get; set; }
```

``` c++
property Decimal CompanyCurrencyAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ITenderLineItemV1 Interface](itenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

