---
title: IRetailTransactionV1.TimeWhenTotalPressed Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TimeWhenTotalPressed Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.TimeWhenTotalPressed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.timewhentotalpressed(v=AX.60)
ms:contentKeyID: 49840383
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.TimeWhenTotalPressed
dev_langs:
- CSharp
- C++
- VB
---

# TimeWhenTotalPressed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The time of the first payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TimeWhenTotalPressed As Integer
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Integer

value = instance.TimeWhenTotalPressed

instance.TimeWhenTotalPressed = value
```

``` csharp
int TimeWhenTotalPressed { get; set; }
```

``` c++
property int TimeWhenTotalPressed {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

