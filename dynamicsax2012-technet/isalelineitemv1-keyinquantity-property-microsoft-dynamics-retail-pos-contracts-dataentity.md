---
title: ISaleLineItemV1.KeyInQuantity Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: KeyInQuantity Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.KeyInQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.keyinquantity(v=AX.60)
ms:contentKeyID: 49847087
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.KeyInQuantity
dev_langs:
- CSharp
- C++
- VB
---

# KeyInQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Rules for keying in quantities for the item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property KeyInQuantity As KeyInQuantities
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As KeyInQuantities

value = instance.KeyInQuantity

instance.KeyInQuantity = value
```

``` csharp
KeyInQuantities KeyInQuantity { get; set; }
```

``` c++
property KeyInQuantities KeyInQuantity {
    KeyInQuantities get ();
    void set (KeyInQuantities value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.KeyInQuantities](keyinquantities-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [KeyInQuantities](keyinquantities-enumeration-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

