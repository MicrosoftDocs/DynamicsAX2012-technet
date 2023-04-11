---
title: IItemV1.TaxationOrigin Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TaxationOrigin Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.TaxationOrigin
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.taxationorigin(v=AX.60)
ms:contentKeyID: 49855578
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.TaxationOrigin
dev_langs:
- CSharp
- C++
- VB
---

# TaxationOrigin Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the taxation origin.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TaxationOrigin As Integer
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Integer

value = instance.TaxationOrigin

instance.TaxationOrigin = value
```

``` csharp
int TaxationOrigin { get; set; }
```

``` c++
property int TaxationOrigin {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The taxation origin.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

