---
title: TradeAgreement.IsQuantityMatch Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsQuantityMatch Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.IsQuantityMatch(System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.isquantitymatch(v=AX.60)
ms:contentKeyID: 62214409
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.IsQuantityMatch
dev_langs:
- CSharp
- C++
- VB
---

# IsQuantityMatch Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether it's match for the quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function IsQuantityMatch ( _
    quantity As Decimal _
) As Boolean
'Usage
Dim instance As TradeAgreement
Dim quantity As Decimal
Dim returnValue As Boolean

returnValue = instance.IsQuantityMatch(quantity)
```

``` csharp
public bool IsQuantityMatch(
    decimal quantity
)
```

``` c++
public:
bool IsQuantityMatch(
    Decimal quantity
)
```

#### Parameters

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether it's match for the quantity.  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

