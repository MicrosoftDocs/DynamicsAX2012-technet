---
title: ITenderV1.MaximumAmountAllowed Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: MaximumAmountAllowed Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.MaximumAmountAllowed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderv1.maximumamountallowed(v=AX.60)
ms:contentKeyID: 49843019
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.MaximumAmountAllowed
dev_langs:
- CSharp
- C++
- VB
---

# MaximumAmountAllowed Property

The highest amount possible to pay

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MaximumAmountAllowed As Decimal
    Get
    Set
'Usage
Dim instance As ITenderV1
Dim value As Decimal

value = instance.MaximumAmountAllowed

instance.MaximumAmountAllowed = value
```

``` csharp
decimal MaximumAmountAllowed { get; set; }
```

``` c++
property Decimal MaximumAmountAllowed {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ITenderV1 Interface](itenderv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

