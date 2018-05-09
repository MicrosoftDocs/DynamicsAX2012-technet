---
title: TradeAgreement.IsVariantExactMatch Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsVariantExactMatch Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.IsVariantExactMatch(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.isvariantexactmatch(v=AX.60)
ms:contentKeyID: 62212375
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.IsVariantExactMatch
dev_langs:
- CSharp
- C++
- VB
---

# IsVariantExactMatch Method

Gets a value indicating whether it's exact match for the variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function IsVariantExactMatch ( _
    variant As ProductVariant _
) As Boolean
'Usage
Dim instance As TradeAgreement
Dim variant As ProductVariant
Dim returnValue As Boolean

returnValue = instance.IsVariantExactMatch(variant)
```

``` csharp
public bool IsVariantExactMatch(
    ProductVariant variant
)
```

``` c++
public:
bool IsVariantExactMatch(
    ProductVariant^ variant
)
```

#### Parameters

  - variant  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
A value indicating whether it's exact match for the variant.  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

