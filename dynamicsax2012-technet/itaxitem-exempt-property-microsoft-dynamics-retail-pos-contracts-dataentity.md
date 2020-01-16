---
title: ITaxItem.Exempt Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Exempt Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem.Exempt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxitem.exempt(v=AX.60)
ms:contentKeyID: 47128795
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem.Exempt
dev_langs:
- CSharp
- C++
- VB
---

# Exempt Property

Gets or sets whether the tax code instance is exempt.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Exempt As Boolean
    Get
    Set
'Usage
Dim instance As ITaxItem
Dim value As Boolean

value = instance.Exempt

instance.Exempt = value
```

``` csharp
bool Exempt { get; set; }
```

``` c++
property bool Exempt {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxItem Interface](itaxitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

