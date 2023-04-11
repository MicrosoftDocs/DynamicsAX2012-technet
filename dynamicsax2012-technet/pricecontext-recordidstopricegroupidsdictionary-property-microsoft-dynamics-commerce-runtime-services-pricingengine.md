---
title: PriceContext.RecordIdsToPriceGroupIdsDictionary Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: RecordIdsToPriceGroupIdsDictionary Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.RecordIdsToPriceGroupIdsDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.recordidstopricegroupidsdictionary(v=AX.60)
ms:contentKeyID: 62213955
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.RecordIdsToPriceGroupIdsDictionary
dev_langs:
- CSharp
- C++
- VB
---

# RecordIdsToPriceGroupIdsDictionary Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the translation between record ids and price group identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property RecordIdsToPriceGroupIdsDictionary As IDictionary(Of Long, String)
    Get
    Private Set
'Usage
Dim instance As PriceContext
Dim value As IDictionary(Of Long, String)

value = instance.RecordIdsToPriceGroupIdsDictionary
```

``` csharp
public IDictionary<long, string> RecordIdsToPriceGroupIdsDictionary { get; private set; }
```

``` c++
public:
property IDictionary<long long, String^>^ RecordIdsToPriceGroupIdsDictionary {
    IDictionary<long long, String^>^ get ();
    private: void set (IDictionary<long long, String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

