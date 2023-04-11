---
title: IItemV1.ItemId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.ItemId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.itemid(v=AX.60)
ms:contentKeyID: 49853094
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.ItemId
dev_langs:
- CSharp
- C++
- VB
---

# ItemId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemId As String
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As String

value = instance.ItemId

instance.ItemId = value
```

``` csharp
string ItemId { get; set; }
```

``` c++
property String^ ItemId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The item id.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

