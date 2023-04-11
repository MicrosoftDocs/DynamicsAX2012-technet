---
title: ProductRules.PriceKeyingRequirement Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceKeyingRequirement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.PriceKeyingRequirement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.pricekeyingrequirement(v=AX.60)
ms:contentKeyID: 62212651
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.PriceKeyingRequirement
dev_langs:
- CSharp
- C++
- VB
---

# PriceKeyingRequirement Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item's price keying requirement.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KEYINGINPRICE")> _
<IgnoreDataMemberAttribute> _
Public Property PriceKeyingRequirement As KeyInPrices
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As KeyInPrices

value = instance.PriceKeyingRequirement
```

``` csharp
[ColumnAttribute("KEYINGINPRICE")]
[IgnoreDataMemberAttribute]
public KeyInPrices PriceKeyingRequirement { get; internal set; }
```

``` c++
[ColumnAttribute(L"KEYINGINPRICE")]
[IgnoreDataMemberAttribute]
public:
property KeyInPrices PriceKeyingRequirement {
    KeyInPrices get ();
    internal: void set (KeyInPrices value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices](keyinprices-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [KeyInPrices](keyinprices-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

