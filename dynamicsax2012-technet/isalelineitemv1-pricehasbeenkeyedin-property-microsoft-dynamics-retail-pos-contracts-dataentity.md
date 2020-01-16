---
title: ISaleLineItemV1.PriceHasBeenKeyedIn Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PriceHasBeenKeyedIn Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.PriceHasBeenKeyedIn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.pricehasbeenkeyedin(v=AX.60)
ms:contentKeyID: 49834314
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.PriceHasBeenKeyedIn
dev_langs:
- CSharp
- C++
- VB
---

# PriceHasBeenKeyedIn Property

True when the price has been keyed in (must key in price option).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PriceHasBeenKeyedIn As Boolean
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Boolean

value = instance.PriceHasBeenKeyedIn

instance.PriceHasBeenKeyedIn = value
```

``` csharp
bool PriceHasBeenKeyedIn { get; set; }
```

``` c++
property bool PriceHasBeenKeyedIn {
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

