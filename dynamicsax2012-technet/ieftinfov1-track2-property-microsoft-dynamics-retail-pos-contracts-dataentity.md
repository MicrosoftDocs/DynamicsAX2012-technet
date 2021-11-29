---
title: IEFTInfoV1.Track2 Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Track2 Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.Track2
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.track2(v=AX.60)
ms:contentKeyID: 47128251
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.Track2
dev_langs:
- CSharp
- C++
- VB
---

# Track2 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Track2 of the magnetic stripe of the card if the card was swiped through a card reader.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Track2 As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As String

value = instance.Track2

instance.Track2 = value
```

``` csharp
string Track2 { get; set; }
```

``` c++
property String^ Track2 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## Remarks

May contain start/stop sentinels

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

