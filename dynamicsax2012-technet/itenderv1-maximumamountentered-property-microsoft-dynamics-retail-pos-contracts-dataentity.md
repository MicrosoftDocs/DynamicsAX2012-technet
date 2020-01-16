---
title: ITenderV1.MaximumAmountEntered Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: MaximumAmountEntered Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.MaximumAmountEntered
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderv1.maximumamountentered(v=AX.60)
ms:contentKeyID: 49821235
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.MaximumAmountEntered
dev_langs:
- CSharp
- C++
- VB
---

# MaximumAmountEntered Property

The highest amount possible to pay in a single payment

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MaximumAmountEntered As Decimal
    Get
    Set
'Usage
Dim instance As ITenderV1
Dim value As Decimal

value = instance.MaximumAmountEntered

instance.MaximumAmountEntered = value
```

``` csharp
decimal MaximumAmountEntered { get; set; }
```

``` c++
property Decimal MaximumAmountEntered {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ITenderV1 Interface](itenderv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

