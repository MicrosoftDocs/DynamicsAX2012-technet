---
title: ICardInfoV1.ExpDateCheck Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ExpDateCheck Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.ExpDateCheck
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.expdatecheck(v=AX.60)
ms:contentKeyID: 47128040
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.ExpDateCheck
dev_langs:
- CSharp
- C++
- VB
---

# ExpDateCheck Property

Gets or sets the expiration date check value.

Set to true if the expiration date for the card should be checked.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ExpDateCheck As Boolean
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As Boolean

value = instance.ExpDateCheck

instance.ExpDateCheck = value
```

``` csharp
bool ExpDateCheck { get; set; }
```

``` c++
property bool ExpDateCheck {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

