---
title: IRetailTransactionV1.LockElapsedTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LockElapsedTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.LockElapsedTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.lockelapsedtime(v=AX.60)
ms:contentKeyID: 49850245
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.LockElapsedTime
dev_langs:
- CSharp
- C++
- VB
---

# LockElapsedTime Property

The total time the terminal was locked during the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LockElapsedTime As TimeSpan
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As TimeSpan

value = instance.LockElapsedTime

instance.LockElapsedTime = value
```

``` csharp
TimeSpan LockElapsedTime { get; set; }
```

``` c++
property TimeSpan LockElapsedTime {
    TimeSpan get ();
    void set (TimeSpan value);
}
```

#### Property Value

Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  
Returns [TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

