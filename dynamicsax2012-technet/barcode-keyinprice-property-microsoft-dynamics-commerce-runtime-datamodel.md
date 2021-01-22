---
title: Barcode.KeyInPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyInPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.KeyInPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.keyinprice(v=AX.60)
ms:contentKeyID: 62208060
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.KeyInPrice
dev_langs:
- CSharp
- C++
- VB
---

# KeyInPrice Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property KeyInPrice As KeyInPrices
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As KeyInPrices

value = instance.KeyInPrice

instance.KeyInPrice = value
```

``` csharp
[IgnoreDataMemberAttribute]
public KeyInPrices KeyInPrice { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property KeyInPrices KeyInPrice {
    KeyInPrices get ();
    void set (KeyInPrices value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices](keyinprices-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

