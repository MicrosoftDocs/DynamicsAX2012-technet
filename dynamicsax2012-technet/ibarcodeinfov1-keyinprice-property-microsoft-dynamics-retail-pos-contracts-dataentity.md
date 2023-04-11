---
title: IBarcodeInfoV1.KeyInPrice Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: KeyInPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.KeyInPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.keyinprice(v=AX.60)
ms:contentKeyID: 47128949
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.KeyInPrice
dev_langs:
- CSharp
- C++
- VB
---

# KeyInPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets an enumerated constant that indicates the key in price.

The rules for keying in prices for the item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property KeyInPrice As KeyInPrices
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As KeyInPrices

value = instance.KeyInPrice

instance.KeyInPrice = value
```

``` csharp
KeyInPrices KeyInPrice { get; set; }
```

``` c++
property KeyInPrices KeyInPrice {
    KeyInPrices get ();
    void set (KeyInPrices value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.KeyInPrices](keyinprices-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.KeyInPrices](keyinprices-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

[KeyInPrices](keyinprices-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)

