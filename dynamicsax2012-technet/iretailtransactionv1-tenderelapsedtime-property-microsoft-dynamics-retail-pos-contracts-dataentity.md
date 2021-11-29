---
title: IRetailTransactionV1.TenderElapsedTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TenderElapsedTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.TenderElapsedTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.tenderelapsedtime(v=AX.60)
ms:contentKeyID: 49832325
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.TenderElapsedTime
dev_langs:
- CSharp
- C++
- VB
---

# TenderElapsedTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The total time the terminal was handling payments.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TenderElapsedTime As TimeSpan
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As TimeSpan

value = instance.TenderElapsedTime

instance.TenderElapsedTime = value
```

``` csharp
TimeSpan TenderElapsedTime { get; set; }
```

``` c++
property TimeSpan TenderElapsedTime {
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

