---
title: IItemV1.SalesPriceModelBasic Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SalesPriceModelBasic Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.SalesPriceModelBasic
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.salespricemodelbasic(v=AX.60)
ms:contentKeyID: 49837442
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.SalesPriceModelBasic
dev_langs:
- CSharp
- C++
- VB
---

# SalesPriceModelBasic Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales price model basic.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SalesPriceModelBasic As Integer
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Integer

value = instance.SalesPriceModelBasic

instance.SalesPriceModelBasic = value
```

``` csharp
int SalesPriceModelBasic { get; set; }
```

``` c++
property int SalesPriceModelBasic {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The sales price model basic.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

