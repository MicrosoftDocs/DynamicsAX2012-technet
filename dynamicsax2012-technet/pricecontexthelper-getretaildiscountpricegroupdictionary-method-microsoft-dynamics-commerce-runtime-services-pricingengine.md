---
title: PriceContextHelper.GetRetailDiscountPriceGroupDictionary Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetRetailDiscountPriceGroupDictionary Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetRetailDiscountPriceGroupDictionary(Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,System.Collections.Generic.ISet{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getretaildiscountpricegroupdictionary(v=AX.60)
ms:contentKeyID: 62213174
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetRetailDiscountPriceGroupDictionary
dev_langs:
- CSharp
- C++
- VB
---

# GetRetailDiscountPriceGroupDictionary Method

Get offer identifier to retail discount price groups dictionary.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetRetailDiscountPriceGroupDictionary ( _
    pricingDataManager As IPricingDataManagerV2, _
    offerIds As ISet(Of String) _
) As IDictionary(Of String, ISet(Of String))
'Usage
Dim pricingDataManager As IPricingDataManagerV2
Dim offerIds As ISet(Of String)
Dim returnValue As IDictionary(Of String, ISet(Of String))

returnValue = PriceContextHelper.GetRetailDiscountPriceGroupDictionary(pricingDataManager, _
    offerIds)
```

``` csharp
public static IDictionary<string, ISet<string>> GetRetailDiscountPriceGroupDictionary(
    IPricingDataManagerV2 pricingDataManager,
    ISet<string> offerIds
)
```

``` c++
public:
static IDictionary<String^, ISet<String^>^>^ GetRetailDiscountPriceGroupDictionary(
    IPricingDataManagerV2^ pricingDataManager, 
    ISet<String^>^ offerIds
)
```

#### Parameters

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - offerIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>\>  
A dictionary of offer identifier to retail discount price groups map.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

