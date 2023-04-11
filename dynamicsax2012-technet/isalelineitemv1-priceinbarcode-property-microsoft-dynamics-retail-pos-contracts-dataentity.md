---
title: ISaleLineItemV1.PriceInBarcode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PriceInBarcode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.PriceInBarcode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.priceinbarcode(v=AX.60)
ms:contentKeyID: 49852357
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.PriceInBarcode
dev_langs:
- CSharp
- C++
- VB
---

# PriceInBarcode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Is set to true if the price was read from the barcode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PriceInBarcode As Boolean
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Boolean

value = instance.PriceInBarcode

instance.PriceInBarcode = value
```

``` csharp
bool PriceInBarcode { get; set; }
```

``` c++
property bool PriceInBarcode {
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

