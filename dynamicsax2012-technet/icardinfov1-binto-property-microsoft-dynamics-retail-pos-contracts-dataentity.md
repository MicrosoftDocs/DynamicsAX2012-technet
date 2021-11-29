---
title: ICardInfoV1.BinTo Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BinTo Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.BinTo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.binto(v=AX.60)
ms:contentKeyID: 47128213
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.BinTo
dev_langs:
- CSharp
- C++
- VB
---

# BinTo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the bin series end value.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BinTo As String
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As String

value = instance.BinTo

instance.BinTo = value
```

``` csharp
string BinTo { get; set; }
```

``` c++
property String^ BinTo {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

