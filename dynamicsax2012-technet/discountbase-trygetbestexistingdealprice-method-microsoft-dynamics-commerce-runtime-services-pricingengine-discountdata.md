---
title: DiscountBase.TryGetBestExistingDealPrice Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: TryGetBestExistingDealPrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.TryGetBestExistingDealPrice(System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.IList{Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountLineQuantity}},System.Int32,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.trygetbestexistingdealprice(v=AX.60)
ms:contentKeyID: 65323189
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.TryGetBestExistingDealPrice
dev_langs:
- CSharp
- C++
- VB
---

# TryGetBestExistingDealPrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function TryGetBestExistingDealPrice ( _
    discountDictionary As Dictionary(Of Integer, IList(Of DiscountLineQuantity)), _
    itemIndex As Integer, _
    <OutAttribute> ByRef bestExistingDealPrice As Decimal _
) As Boolean
'Usage
Dim discountDictionary As Dictionary(Of Integer, IList(Of DiscountLineQuantity))
Dim itemIndex As Integer
Dim bestExistingDealPrice As Decimal
Dim returnValue As Boolean

returnValue = DiscountBase.TryGetBestExistingDealPrice(discountDictionary, _
    itemIndex, bestExistingDealPrice)
```

``` csharp
protected static bool TryGetBestExistingDealPrice(
    Dictionary<int, IList<DiscountLineQuantity>> discountDictionary,
    int itemIndex,
    out decimal bestExistingDealPrice
)
```

``` c++
protected:
static bool TryGetBestExistingDealPrice(
    Dictionary<int, IList<DiscountLineQuantity^>^>^ discountDictionary, 
    int itemIndex, 
    [OutAttribute] Decimal% bestExistingDealPrice
)
```

#### Parameters

  - discountDictionary  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)), [IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[DiscountLineQuantity](discountlinequantity-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>\>  

<!-- end list -->

  - itemIndex  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - bestExistingDealPrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

