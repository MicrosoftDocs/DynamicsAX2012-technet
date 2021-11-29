---
title: IItemV1.ItemDimCostPrice Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemDimCostPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.ItemDimCostPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.itemdimcostprice(v=AX.60)
ms:contentKeyID: 49839124
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.ItemDimCostPrice
dev_langs:
- CSharp
- C++
- VB
---

# ItemDimCostPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item dim cost price.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemDimCostPrice As Integer
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Integer

value = instance.ItemDimCostPrice

instance.ItemDimCostPrice = value
```

``` csharp
int ItemDimCostPrice { get; set; }
```

``` c++
property int ItemDimCostPrice {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The item dim cost price.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

