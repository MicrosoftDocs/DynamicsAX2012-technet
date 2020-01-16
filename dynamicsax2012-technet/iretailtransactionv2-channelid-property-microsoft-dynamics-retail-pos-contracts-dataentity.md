---
title: IRetailTransactionV2.ChannelId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ChannelId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.ChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv2.channelid(v=AX.60)
ms:contentKeyID: 49837016
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.ChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelId Property

Id of the originating Channel

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ChannelId As Long
    Get
    Set
'Usage
Dim instance As IRetailTransactionV2
Dim value As Long

value = instance.ChannelId

instance.ChannelId = value
```

``` csharp
long ChannelId { get; set; }
```

``` c++
property long long ChannelId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV2 Interface](iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

