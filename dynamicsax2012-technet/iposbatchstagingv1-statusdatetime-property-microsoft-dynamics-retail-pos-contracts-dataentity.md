---
title: IPosBatchStagingV1.StatusDateTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: StatusDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStagingV1.StatusDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iposbatchstagingv1.statusdatetime(v=AX.60)
ms:contentKeyID: 47129160
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStagingV1.StatusDateTime
dev_langs:
- CSharp
- C++
- VB
---

# StatusDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the current status date and time.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property StatusDateTime As DateTime
    Get
    Set
'Usage
Dim instance As IPosBatchStagingV1
Dim value As DateTime

value = instance.StatusDateTime

instance.StatusDateTime = value
```

``` csharp
DateTime StatusDateTime { get; set; }
```

``` c++
property DateTime StatusDateTime {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
The [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosBatchStagingV1 Interface](iposbatchstagingv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

