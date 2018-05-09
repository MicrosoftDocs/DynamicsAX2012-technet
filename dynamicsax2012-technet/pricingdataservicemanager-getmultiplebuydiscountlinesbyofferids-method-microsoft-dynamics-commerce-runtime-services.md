---
title: PricingDataServiceManager.GetMultipleBuyDiscountLinesByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetMultipleBuyDiscountLinesByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetMultipleBuyDiscountLinesByOfferIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getmultiplebuydiscountlinesbyofferids(v=AX.60)
ms:contentKeyID: 65321663
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetMultipleBuyDiscountLinesByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# GetMultipleBuyDiscountLinesByOfferIds Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetMultipleBuyDiscountLinesByOfferIds ( _
    offerIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of QuantityDiscountLevel)
'Usage
Dim instance As PricingDataServiceManager
Dim offerIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of QuantityDiscountLevel)

returnValue = instance.GetMultipleBuyDiscountLinesByOfferIds(offerIds)
```

``` csharp
public ReadOnlyCollection<QuantityDiscountLevel> GetMultipleBuyDiscountLinesByOfferIds(
    IEnumerable<string> offerIds
)
```

``` c++
public:
virtual ReadOnlyCollection<QuantityDiscountLevel^>^ GetMultipleBuyDiscountLinesByOfferIds(
    IEnumerable<String^>^ offerIds
) sealed
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManagerV2.GetMultipleBuyDiscountLinesByOfferIds(IEnumerable\<String\>)](ipricingdatamanagerv2-getmultiplebuydiscountlinesbyofferids-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

