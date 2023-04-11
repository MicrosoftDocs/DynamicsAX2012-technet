---
title: ICardInfoV1.EnterFleetInfo Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EnterFleetInfo Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.EnterFleetInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.enterfleetinfo(v=AX.60)
ms:contentKeyID: 47128574
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.EnterFleetInfo
dev_langs:
- CSharp
- C++
- VB
---

# EnterFleetInfo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets “enter fleet” information.

Set to true if fleet information must be entered for the card. This should be true only for special fleet cards.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EnterFleetInfo As Boolean
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As Boolean

value = instance.EnterFleetInfo

instance.EnterFleetInfo = value
```

``` csharp
bool EnterFleetInfo { get; set; }
```

``` c++
property bool EnterFleetInfo {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

