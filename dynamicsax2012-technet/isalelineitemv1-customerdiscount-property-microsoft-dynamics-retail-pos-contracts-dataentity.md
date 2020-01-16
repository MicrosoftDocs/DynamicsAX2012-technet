---
title: ISaleLineItemV1.CustomerDiscount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CustomerDiscount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.CustomerDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.customerdiscount(v=AX.60)
ms:contentKeyID: 49837077
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.CustomerDiscount
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDiscount Property

Total customer discount given in this transaction (excluding tax)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CustomerDiscount As Decimal
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Decimal

value = instance.CustomerDiscount

instance.CustomerDiscount = value
```

``` csharp
decimal CustomerDiscount { get; set; }
```

``` c++
property Decimal CustomerDiscount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

