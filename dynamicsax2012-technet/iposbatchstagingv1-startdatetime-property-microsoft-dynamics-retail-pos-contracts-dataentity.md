---
title: IPosBatchStagingV1.StartDateTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: StartDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStagingV1.StartDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iposbatchstagingv1.startdatetime(v=AX.60)
ms:contentKeyID: 47129329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStagingV1.StartDateTime
dev_langs:
- CSharp
- C++
- VB
---

# StartDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the start date and time of the batch.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property StartDateTime As DateTime
    Get
'Usage
Dim instance As IPosBatchStagingV1
Dim value As DateTime

value = instance.StartDateTime
```

``` csharp
DateTime StartDateTime { get; }
```

``` c++
property DateTime StartDateTime {
    DateTime get ();
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
The [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosBatchStagingV1 Interface](iposbatchstagingv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

