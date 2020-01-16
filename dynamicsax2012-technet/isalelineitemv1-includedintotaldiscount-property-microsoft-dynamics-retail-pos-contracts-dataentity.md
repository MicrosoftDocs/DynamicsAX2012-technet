---
title: ISaleLineItemV1.IncludedInTotalDiscount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IncludedInTotalDiscount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.IncludedInTotalDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.includedintotaldiscount(v=AX.60)
ms:contentKeyID: 49853290
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.IncludedInTotalDiscount
dev_langs:
- CSharp
- C++
- VB
---

# IncludedInTotalDiscount Property

Is true if the item included in the calculation of a combined total discount. Should be set when the item info is found.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IncludedInTotalDiscount As Boolean
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
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
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

