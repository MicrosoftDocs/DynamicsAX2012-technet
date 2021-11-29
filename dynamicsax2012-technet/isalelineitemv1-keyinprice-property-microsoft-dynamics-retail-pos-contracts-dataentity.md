---
title: ISaleLineItemV1.KeyInPrice Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: KeyInPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.KeyInPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.keyinprice(v=AX.60)
ms:contentKeyID: 49835828
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.KeyInPrice
dev_langs:
- CSharp
- C++
- VB
---

# KeyInPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Rules for keying in prices for the item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property KeyInPrice As KeyInPrices
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
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
Returns [KeyInPrices](keyinprices-enumeration-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

