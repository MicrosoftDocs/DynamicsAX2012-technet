---
title: MixAndMatchDiscount.LineGroupToNumberOfItemsMap Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: LineGroupToNumberOfItemsMap Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.MixAndMatchDiscount.LineGroupToNumberOfItemsMap
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.mixandmatchdiscount.linegrouptonumberofitemsmap(v=AX.60)
ms:contentKeyID: 62211750
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.MixAndMatchDiscount.LineGroupToNumberOfItemsMap
dev_langs:
- CSharp
- C++
- VB
---

# LineGroupToNumberOfItemsMap Property

Gets the map of mix and match line group to number of items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property LineGroupToNumberOfItemsMap As IDictionary(Of String, Integer)
    Get
    Private Set
'Usage
Dim instance As MixAndMatchDiscount
Dim value As IDictionary(Of String, Integer)

value = instance.LineGroupToNumberOfItemsMap
```

``` csharp
public IDictionary<string, int> LineGroupToNumberOfItemsMap { get; private set; }
```

``` c++
public:
property IDictionary<String^, int>^ LineGroupToNumberOfItemsMap {
    IDictionary<String^, int>^ get ();
    private: void set (IDictionary<String^, int>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[MixAndMatchDiscount Class](mixandmatchdiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

