---
title: ISaleLineItemV1.ReturnLineId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ReturnLineId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.ReturnLineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.returnlineid(v=AX.60)
ms:contentKeyID: 49824866
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.ReturnLineId
dev_langs:
- CSharp
- C++
- VB
---

# ReturnLineId Property

// If the item is being returned, this field stores the item's line id in the original transaction the item was sold in.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ReturnLineId As Integer
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Integer

value = instance.ReturnLineId

instance.ReturnLineId = value
```

``` csharp
int ReturnLineId { get; set; }
```

``` c++
property int ReturnLineId {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

