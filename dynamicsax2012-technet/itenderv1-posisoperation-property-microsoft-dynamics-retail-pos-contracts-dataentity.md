---
title: ITenderV1.PosisOperation Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PosisOperation Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.PosisOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderv1.posisoperation(v=AX.60)
ms:contentKeyID: 49834870
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.PosisOperation
dev_langs:
- CSharp
- C++
- VB
---

# PosisOperation Property

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PosisOperation As PosisOperations
    Get
    Set
'Usage
Dim instance As ITenderV1
Dim value As PosisOperations

value = instance.PosisOperation

instance.PosisOperation = value
```

``` csharp
PosisOperations PosisOperation { get; set; }
```

``` c++
property PosisOperations PosisOperation {
    PosisOperations get ();
    void set (PosisOperations value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  
Returns [PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md).  

## See Also

#### Reference

[ITenderV1 Interface](itenderv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

