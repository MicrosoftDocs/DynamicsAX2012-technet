---
title: IRetailTransactionV1.NoOfItemLines Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: NoOfItemLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.NoOfItemLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.noofitemlines(v=AX.60)
ms:contentKeyID: 49853318
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.NoOfItemLines
dev_langs:
- CSharp
- C++
- VB
---

# NoOfItemLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Number of the item lines, not the qty of the items

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property NoOfItemLines As Decimal
    Get
'Usage
Dim instance As IRetailTransactionV1
Dim value As Decimal

value = instance.NoOfItemLines
```

``` csharp
decimal NoOfItemLines { get; }
```

``` c++
property Decimal NoOfItemLines {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

