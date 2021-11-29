---
title: DiscountableItemGroup.ApplyDiscountLines Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ApplyDiscountLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.ApplyDiscountLines(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountableitemgroup.applydiscountlines(v=AX.60)
ms:contentKeyID: 65321894
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.ApplyDiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# ApplyDiscountLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Sub ApplyDiscountLines ( _
    transaction As SalesTransaction, _
    isReturn As Boolean _
)
'Usage
Dim instance As DiscountableItemGroup
Dim transaction As SalesTransaction
Dim isReturn As Boolean

instance.ApplyDiscountLines(transaction, _
    isReturn)
```

``` csharp
public void ApplyDiscountLines(
    SalesTransaction transaction,
    bool isReturn
)
```

``` c++
public:
void ApplyDiscountLines(
    SalesTransaction^ transaction, 
    bool isReturn
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - isReturn  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[DiscountableItemGroup Class](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

