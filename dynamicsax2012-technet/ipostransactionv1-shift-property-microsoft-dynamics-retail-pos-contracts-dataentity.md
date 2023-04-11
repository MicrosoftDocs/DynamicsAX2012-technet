---
title: IPosTransactionV1.Shift Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Shift Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.Shift
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.shift(v=AX.60)
ms:contentKeyID: 47128591
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.Shift
dev_langs:
- CSharp
- C++
- VB
---

# Shift Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shift for the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Shift As IPosBatchStaging
    Get
    Set
'Usage
Dim instance As IPosTransactionV1
Dim value As IPosBatchStaging

value = instance.Shift

instance.Shift = value
```

``` csharp
IPosBatchStaging Shift { get; set; }
```

``` c++
property IPosBatchStaging^ Shift {
    IPosBatchStaging^ get ();
    void set (IPosBatchStaging^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStaging](iposbatchstaging-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStaging](iposbatchstaging-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

