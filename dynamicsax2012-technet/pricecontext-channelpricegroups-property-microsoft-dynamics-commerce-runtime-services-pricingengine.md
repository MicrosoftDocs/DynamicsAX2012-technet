---
title: PriceContext.ChannelPriceGroups Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: ChannelPriceGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.ChannelPriceGroups
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.channelpricegroups(v=AX.60)
ms:contentKeyID: 62210283
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.ChannelPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# ChannelPriceGroups Property

Gets the collection of channel price groups to search by.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property ChannelPriceGroups As ISet(Of String)
    Get
    Private Set
'Usage
Dim instance As PriceContext
Dim value As ISet(Of String)

value = instance.ChannelPriceGroups
```

``` csharp
public ISet<string> ChannelPriceGroups { get; private set; }
```

``` c++
public:
property ISet<String^>^ ChannelPriceGroups {
    ISet<String^>^ get ();
    private: void set (ISet<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ISet\<T\>](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\)).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

