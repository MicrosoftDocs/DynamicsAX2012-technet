---
title: ICardInfoV2.IsTokenMode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IsTokenMode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV2.IsTokenMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov2.istokenmode(v=AX.60)
ms:contentKeyID: 49837532
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV2.IsTokenMode
dev_langs:
- CSharp
- C++
- VB
---

# IsTokenMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Need just credit card information to fetch a token

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IsTokenMode As Boolean
    Get
    Set
'Usage
Dim instance As ICardInfoV2
Dim value As Boolean

value = instance.IsTokenMode

instance.IsTokenMode = value
```

``` csharp
bool IsTokenMode { get; set; }
```

``` c++
property bool IsTokenMode {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ICardInfoV2 Interface](icardinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

