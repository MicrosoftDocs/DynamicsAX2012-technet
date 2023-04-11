---
title: DiscountBase.InitializeDiscountDictionary Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: InitializeDiscountDictionary Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.InitializeDiscountDictionary(System.Collections.Generic.Stack{Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.AppliedDiscountApplication},System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.IList{Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountLineQuantity}},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.initializediscountdictionary(v=AX.60)
ms:contentKeyID: 65319196
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.InitializeDiscountDictionary
dev_langs:
- CSharp
- C++
- VB
---

# InitializeDiscountDictionary Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function InitializeDiscountDictionary ( _
    appliedDiscounts As Stack(Of AppliedDiscountApplication), _
    discountDictionary As Dictionary(Of Integer, IList(Of DiscountLineQuantity)), _
    countThreshold As Boolean _
) As Boolean
'Usage
Dim appliedDiscounts As Stack(Of AppliedDiscountApplication)
Dim discountDictionary As Dictionary(Of Integer, IList(Of DiscountLineQuantity))
Dim countThreshold As Boolean
Dim returnValue As Boolean

returnValue = Me.InitializeDiscountDictionary(appliedDiscounts, _
    discountDictionary, countThreshold)
```

``` csharp
protected bool InitializeDiscountDictionary(
    Stack<AppliedDiscountApplication> appliedDiscounts,
    Dictionary<int, IList<DiscountLineQuantity>> discountDictionary,
    bool countThreshold
)
```

``` c++
protected:
bool InitializeDiscountDictionary(
    Stack<AppliedDiscountApplication^>^ appliedDiscounts, 
    Dictionary<int, IList<DiscountLineQuantity^>^>^ discountDictionary, 
    bool countThreshold
)
```

#### Parameters

  - appliedDiscounts  
    Type: [System.Collections.Generic.Stack](https://technet.microsoft.com/library/3278tedw\(v=ax.60\))\<[AppliedDiscountApplication](applieddiscountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>  

<!-- end list -->

  - discountDictionary  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)), [IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[DiscountLineQuantity](discountlinequantity-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>\>  

<!-- end list -->

  - countThreshold  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

