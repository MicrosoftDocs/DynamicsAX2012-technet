---
title: IEFTInfoV1.BatchNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BatchNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.BatchNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.batchnumber(v=AX.60)
ms:contentKeyID: 47128115
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.BatchNumber
dev_langs:
- CSharp
- C++
- VB
---

# BatchNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The current batch number for the terminal.

The number can be read after each transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BatchNumber As Long
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As Long

value = instance.BatchNumber

instance.BatchNumber = value
```

``` csharp
long BatchNumber { get; set; }
```

``` c++
property long long BatchNumber {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

