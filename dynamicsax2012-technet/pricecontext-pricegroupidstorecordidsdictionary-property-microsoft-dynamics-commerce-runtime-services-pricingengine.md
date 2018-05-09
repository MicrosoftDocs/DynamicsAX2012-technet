---
title: PriceContext.PriceGroupIdsToRecordIdsDictionary Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: PriceGroupIdsToRecordIdsDictionary Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.PriceGroupIdsToRecordIdsDictionary
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.pricegroupidstorecordidsdictionary(v=AX.60)
ms:contentKeyID: 62208309
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.PriceGroupIdsToRecordIdsDictionary
dev_langs:
- CSharp
- C++
- VB
---

# PriceGroupIdsToRecordIdsDictionary Property

Gets the translation between price group identifiers and record ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property PriceGroupIdsToRecordIdsDictionary As IDictionary(Of String, Long)
    Get
    Private Set
'Usage
Dim instance As PriceContext
Dim value As IDictionary(Of String, Long)

value = instance.PriceGroupIdsToRecordIdsDictionary
```

``` csharp
public IDictionary<string, long> PriceGroupIdsToRecordIdsDictionary { get; private set; }
```

``` c++
public:
property IDictionary<String^, long long>^ PriceGroupIdsToRecordIdsDictionary {
    IDictionary<String^, long long>^ get ();
    private: void set (IDictionary<String^, long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

