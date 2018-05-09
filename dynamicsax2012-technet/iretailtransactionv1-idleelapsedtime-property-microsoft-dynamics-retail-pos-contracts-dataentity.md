---
title: IRetailTransactionV1.IdleElapsedTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IdleElapsedTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.IdleElapsedTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.idleelapsedtime(v=AX.60)
ms:contentKeyID: 49825292
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.IdleElapsedTime
dev_langs:
- CSharp
- C++
- VB
---

# IdleElapsedTime Property

The total time the terminal was idle during the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IdleElapsedTime As TimeSpan
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As TimeSpan

value = instance.IdleElapsedTime

instance.IdleElapsedTime = value
```

``` csharp
TimeSpan IdleElapsedTime { get; set; }
```

``` c++
property TimeSpan IdleElapsedTime {
    TimeSpan get ();
    void set (TimeSpan value);
}
```

#### Property Value

Type: [System.TimeSpan](https://technet.microsoft.com/en-us/library/269ew577\(v=ax.60\))  
Returns [TimeSpan](https://technet.microsoft.com/en-us/library/269ew577\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

