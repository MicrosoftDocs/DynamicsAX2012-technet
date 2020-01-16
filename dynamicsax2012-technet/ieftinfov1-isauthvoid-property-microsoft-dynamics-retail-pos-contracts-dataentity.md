---
title: IEFTInfoV1.IsAuthVoid Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IsAuthVoid Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.IsAuthVoid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.isauthvoid(v=AX.60)
ms:contentKeyID: 47128576
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.IsAuthVoid
dev_langs:
- CSharp
- C++
- VB
---

# IsAuthVoid Property

True if the authorize transaction was cancelled; false if the transaction was not cancelled.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IsAuthVoid As Boolean
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As Boolean

value = instance.IsAuthVoid

instance.IsAuthVoid = value
```

``` csharp
bool IsAuthVoid { get; set; }
```

``` c++
property bool IsAuthVoid {
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

