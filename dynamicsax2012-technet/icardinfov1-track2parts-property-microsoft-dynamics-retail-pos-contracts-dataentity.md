---
title: ICardInfoV1.Track2Parts Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Track2Parts Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.Track2Parts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.track2parts(v=AX.60)
ms:contentKeyID: 47128651
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.Track2Parts
dev_langs:
- CSharp
- C++
- VB
---

# Track2Parts Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

TrackParts are the two parts of Track2 that are separated by the card separator character.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Track2Parts As String()
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As String()

value = instance.Track2Parts

instance.Track2Parts = value
```

``` csharp
string[] Track2Parts { get; set; }
```

``` c++
property array<String^>^ Track2Parts {
    array<String^>^ get ();
    void set (array<String^>^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

