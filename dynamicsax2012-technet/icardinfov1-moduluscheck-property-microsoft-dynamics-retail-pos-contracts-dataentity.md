---
title: ICardInfoV1.ModulusCheck Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ModulusCheck Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.ModulusCheck
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.moduluscheck(v=AX.60)
ms:contentKeyID: 47128232
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.ModulusCheck
dev_langs:
- CSharp
- C++
- VB
---

# ModulusCheck Property

Gets or sets the modules check.

Set to true if the card number should perform a modulus check.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ModulusCheck As Boolean
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As Boolean

value = instance.ModulusCheck

instance.ModulusCheck = value
```

``` csharp
bool ModulusCheck { get; set; }
```

``` c++
property bool ModulusCheck {
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

