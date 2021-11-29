---
title: TradeAgreement.IsVariantMatch Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsVariantMatch Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.IsVariantMatch(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.isvariantmatch(v=AX.60)
ms:contentKeyID: 62211255
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.IsVariantMatch
dev_langs:
- CSharp
- C++
- VB
---

# IsVariantMatch Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether it's match for the variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function IsVariantMatch ( _
    variant As ProductVariant _
) As Boolean
'Usage
Dim instance As TradeAgreement
Dim variant As ProductVariant
Dim returnValue As Boolean

returnValue = instance.IsVariantMatch(variant)
```

``` csharp
public bool IsVariantMatch(
    ProductVariant variant
)
```

``` c++
public:
bool IsVariantMatch(
    ProductVariant^ variant
)
```

#### Parameters

  - variant  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether it's match for the variant.  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

