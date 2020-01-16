---
title: ITaxableItem.SalesTaxGroupIdOriginal Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SalesTaxGroupIdOriginal Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.SalesTaxGroupIdOriginal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.salestaxgroupidoriginal(v=AX.60)
ms:contentKeyID: 47128377
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.SalesTaxGroupIdOriginal
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxGroupIdOriginal Property

Gets or sets the original sales tax group ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SalesTaxGroupIdOriginal As String
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As String

value = instance.SalesTaxGroupIdOriginal

instance.SalesTaxGroupIdOriginal = value
```

``` csharp
string SalesTaxGroupIdOriginal { get; set; }
```

``` c++
property String^ SalesTaxGroupIdOriginal {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The originl sales tax group ID.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

