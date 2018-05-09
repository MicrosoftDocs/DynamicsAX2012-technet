---
title: IRetailTransactionV2.ChannelReferenceId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ChannelReferenceId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.ChannelReferenceId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv2.channelreferenceid(v=AX.60)
ms:contentKeyID: 49841391
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.ChannelReferenceId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelReferenceId Property

Reference ID set by the originating Channel

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ChannelReferenceId As String
    Get
    Set
'Usage
Dim instance As IRetailTransactionV2
Dim value As String

value = instance.ChannelReferenceId

instance.ChannelReferenceId = value
```

``` csharp
string ChannelReferenceId { get; set; }
```

``` c++
property String^ ChannelReferenceId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV2 Interface](iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

