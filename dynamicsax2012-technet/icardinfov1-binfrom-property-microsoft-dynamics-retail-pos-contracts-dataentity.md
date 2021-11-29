---
title: ICardInfoV1.BinFrom Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BinFrom Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.BinFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.binfrom(v=AX.60)
ms:contentKeyID: 47129044
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.BinFrom
dev_langs:
- CSharp
- C++
- VB
---

# BinFrom Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the bin series start value.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BinFrom As String
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As String

value = instance.BinFrom

instance.BinFrom = value
```

``` csharp
string BinFrom { get; set; }
```

``` c++
property String^ BinFrom {
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

