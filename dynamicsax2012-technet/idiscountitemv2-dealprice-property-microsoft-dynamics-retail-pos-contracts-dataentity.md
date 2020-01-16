---
title: IDiscountItemV2.DealPrice Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DealPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItemV2.DealPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.idiscountitemv2.dealprice(v=AX.60)
ms:contentKeyID: 62205785
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItemV2.DealPrice
dev_langs:
- CSharp
- C++
- VB
---

# DealPrice Property

Gets or sets the deal price.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DealPrice As Decimal
    Get
    Set
'Usage
Dim instance As IDiscountItemV2
Dim value As Decimal

value = instance.DealPrice

instance.DealPrice = value
```

``` csharp
decimal DealPrice { get; set; }
```

``` c++
property Decimal DealPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IDiscountItemV2 Interface](idiscountitemv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

