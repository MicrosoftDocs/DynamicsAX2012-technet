---
title: IEFTInfoV2.Track4 Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Track4 Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV2.Track4
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov2.track4(v=AX.60)
ms:contentKeyID: 49850343
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV2.Track4
dev_langs:
- CSharp
- C++
- VB
---

# Track4 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Track4 of the magnetic stripe of the card - if the card was swept through a card reader

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Track4 As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV2
Dim value As String

value = instance.Track4

instance.Track4 = value
```

``` csharp
string Track4 { get; set; }
```

``` c++
property String^ Track4 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

May contain start/stop sentinels

## See Also

#### Reference

[IEFTInfoV2 Interface](ieftinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

