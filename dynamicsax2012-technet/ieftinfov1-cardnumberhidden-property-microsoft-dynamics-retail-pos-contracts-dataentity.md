---
title: IEFTInfoV1.CardNumberHidden Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CardNumberHidden Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.CardNumberHidden
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.cardnumberhidden(v=AX.60)
ms:contentKeyID: 47128780
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.CardNumberHidden
dev_langs:
- CSharp
- C++
- VB
---

# CardNumberHidden Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the card number hidden. If so, the POS assumes it needs to ask for the card number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CardNumberHidden As Boolean
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As Boolean

value = instance.CardNumberHidden

instance.CardNumberHidden = value
```

``` csharp
bool CardNumberHidden { get; set; }
```

``` c++
property bool CardNumberHidden {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

