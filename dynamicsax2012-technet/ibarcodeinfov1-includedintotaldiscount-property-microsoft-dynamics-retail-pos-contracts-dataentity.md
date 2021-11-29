---
title: IBarcodeInfoV1.IncludedInTotalDiscount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IncludedInTotalDiscount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.IncludedInTotalDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.includedintotaldiscount(v=AX.60)
ms:contentKeyID: 47128264
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.IncludedInTotalDiscount
dev_langs:
- CSharp
- C++
- VB
---

# IncludedInTotalDiscount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets included in total discount.

If returns true, the item is included in the calculation of a combined total discount.

This should be set when the item information is found.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IncludedInTotalDiscount As Boolean
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As Boolean

value = instance.IncludedInTotalDiscount

instance.IncludedInTotalDiscount = value
```

``` csharp
bool IncludedInTotalDiscount { get; set; }
```

``` c++
property bool IncludedInTotalDiscount {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

