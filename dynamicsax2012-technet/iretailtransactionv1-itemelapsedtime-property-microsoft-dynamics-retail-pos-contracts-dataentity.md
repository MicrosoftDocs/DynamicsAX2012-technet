---
title: IRetailTransactionV1.ItemElapsedTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemElapsedTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.ItemElapsedTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.itemelapsedtime(v=AX.60)
ms:contentKeyID: 49838287
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.ItemElapsedTime
dev_langs:
- CSharp
- C++
- VB
---

# ItemElapsedTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The total time the terminal was handling items.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemElapsedTime As TimeSpan
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As TimeSpan

value = instance.ItemElapsedTime

instance.ItemElapsedTime = value
```

``` csharp
TimeSpan ItemElapsedTime { get; set; }
```

``` c++
property TimeSpan ItemElapsedTime {
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

