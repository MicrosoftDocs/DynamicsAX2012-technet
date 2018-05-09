---
title: PricingDataManager.GetMultipleBuyDiscountLinesByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetMultipleBuyDiscountLinesByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetMultipleBuyDiscountLinesByOfferIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.getmultiplebuydiscountlinesbyofferids(v=AX.60)
ms:contentKeyID: 62215109
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetMultipleBuyDiscountLinesByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# GetMultipleBuyDiscountLinesByOfferIds Method

Get all the multi buy discount lines associated with the given offers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetMultipleBuyDiscountLinesByOfferIds ( _
    offerIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of QuantityDiscountLevel)
'Usage
Dim instance As PricingDataManager
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
Collection of multi buy discount lines associated with the given offer Ids.  

#### Implements

[IPricingDataManagerV2.GetMultipleBuyDiscountLinesByOfferIds(IEnumerable\<String\>)](ipricingdatamanagerv2-getmultiplebuydiscountlinesbyofferids-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

