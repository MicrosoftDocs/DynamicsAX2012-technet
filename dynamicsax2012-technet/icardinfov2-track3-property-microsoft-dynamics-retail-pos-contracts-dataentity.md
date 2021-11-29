---
title: ICardInfoV2.Track3 Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Track3 Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV2.Track3
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov2.track3(v=AX.60)
ms:contentKeyID: 49821805
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV2.Track3
dev_langs:
- CSharp
- C++
- VB
---

# Track3 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Track3 of the magnetic stripe of the card - if the card was swept through a card reader.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Track3 As String
    Get
    Set
'Usage
Dim instance As ICardInfoV2
Dim value As String

value = instance.Track3

instance.Track3 = value
```

``` csharp
string Track3 { get; set; }
```

``` c++
property String^ Track3 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICardInfoV2 Interface](icardinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

