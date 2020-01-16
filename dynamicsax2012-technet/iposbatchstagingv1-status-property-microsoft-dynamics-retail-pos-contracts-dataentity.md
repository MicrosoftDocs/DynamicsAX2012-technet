---
title: IPosBatchStagingV1.Status Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStagingV1.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iposbatchstagingv1.status(v=AX.60)
ms:contentKeyID: 47128416
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStagingV1.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property

Gets or sets the status of the batch.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Status As PosBatchStatus
    Get
    Set
'Usage
Dim instance As IPosBatchStagingV1
Dim value As PosBatchStatus

value = instance.Status

instance.Status = value
```

``` csharp
PosBatchStatus Status { get; set; }
```

``` c++
property PosBatchStatus Status {
    PosBatchStatus get ();
    void set (PosBatchStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus](posbatchstatus-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus](posbatchstatus-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md) value.  

## See Also

#### Reference

[IPosBatchStagingV1 Interface](iposbatchstagingv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

