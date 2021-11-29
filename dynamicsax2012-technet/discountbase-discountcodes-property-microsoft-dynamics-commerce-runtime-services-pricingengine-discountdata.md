---
title: DiscountBase.DiscountCodes Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.DiscountCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.discountcodes(v=AX.60)
ms:contentKeyID: 62208686
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.DiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCodes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection containing all of the discount codes that can trigger this discount, if one is required.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property DiscountCodes As ISet(Of String)
    Get
    Private Set
'Usage
Dim instance As DiscountBase
Dim value As ISet(Of String)

value = instance.DiscountCodes
```

``` csharp
public ISet<string> DiscountCodes { get; private set; }
```

``` c++
public:
property ISet<String^>^ DiscountCodes {
    ISet<String^>^ get ();
    private: void set (ISet<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ISet\<T\>](https://technet.microsoft.com/library/dd412081\(v=ax.60\)).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

