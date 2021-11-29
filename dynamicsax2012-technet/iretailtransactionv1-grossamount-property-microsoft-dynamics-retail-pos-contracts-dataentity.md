---
title: IRetailTransactionV1.GrossAmount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: GrossAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.GrossAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.grossamount(v=AX.60)
ms:contentKeyID: 49838555
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.GrossAmount
dev_langs:
- CSharp
- C++
- VB
---

# GrossAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The total amount excluding tax;

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property GrossAmount As Decimal
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Decimal

value = instance.GrossAmount

instance.GrossAmount = value
```

``` csharp
decimal GrossAmount { get; set; }
```

``` c++
property Decimal GrossAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

