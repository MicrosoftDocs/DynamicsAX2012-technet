---
title: IItemV1.NameAlias Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: NameAlias Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.NameAlias
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.namealias(v=AX.60)
ms:contentKeyID: 49826751
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.NameAlias
dev_langs:
- CSharp
- C++
- VB
---

# NameAlias Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the name alias.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property NameAlias As String
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As String

value = instance.NameAlias

instance.NameAlias = value
```

``` csharp
string NameAlias { get; set; }
```

``` c++
property String^ NameAlias {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name alias.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

