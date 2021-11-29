---
title: IItemV1.ItemDimCombinationAutoCreate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemDimCombinationAutoCreate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.ItemDimCombinationAutoCreate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.itemdimcombinationautocreate(v=AX.60)
ms:contentKeyID: 49832974
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.ItemDimCombinationAutoCreate
dev_langs:
- CSharp
- C++
- VB
---

# ItemDimCombinationAutoCreate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item dim combination auto create.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemDimCombinationAutoCreate As Integer
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Integer

value = instance.ItemDimCombinationAutoCreate

instance.ItemDimCombinationAutoCreate = value
```

``` csharp
int ItemDimCombinationAutoCreate { get; set; }
```

``` c++
property int ItemDimCombinationAutoCreate {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The item dim combination auto create.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

