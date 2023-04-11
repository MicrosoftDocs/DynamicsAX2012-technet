---
title: ITaxableItem.SalesTaxGroupId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SalesTaxGroupId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.SalesTaxGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.salestaxgroupid(v=AX.60)
ms:contentKeyID: 47128195
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.SalesTaxGroupId
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales tax group ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SalesTaxGroupId As String
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As String

value = instance.SalesTaxGroupId

instance.SalesTaxGroupId = value
```

``` csharp
string SalesTaxGroupId { get; set; }
```

``` c++
property String^ SalesTaxGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The sales tax group ID.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

