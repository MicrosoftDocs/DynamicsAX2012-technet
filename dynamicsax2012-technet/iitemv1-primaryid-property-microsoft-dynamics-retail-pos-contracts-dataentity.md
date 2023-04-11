---
title: IItemV1.PrimaryId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PrimaryId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PrimaryId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.primaryid(v=AX.60)
ms:contentKeyID: 49825233
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PrimaryId
dev_langs:
- CSharp
- C++
- VB
---

# PrimaryId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the primary id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PrimaryId As Long
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Long

value = instance.PrimaryId

instance.PrimaryId = value
```

``` csharp
long PrimaryId { get; set; }
```

``` c++
property long long PrimaryId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The primary id.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

