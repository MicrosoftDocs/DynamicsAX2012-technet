---
title: ICachedPricingDataManager.PutMultipleBuyDiscountLinesByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutMultipleBuyDiscountLinesByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutMultipleBuyDiscountLinesByOfferIds(System.Collections.Generic.IEnumerable{System.String},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putmultiplebuydiscountlinesbyofferids(v=AX.60)
ms:contentKeyID: 62210645
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutMultipleBuyDiscountLinesByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# PutMultipleBuyDiscountLinesByOfferIds Method

Stores the result of a call to retrieve the multi buy discount lines by offer ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutMultipleBuyDiscountLinesByOfferIds ( _
    offerIds As IEnumerable(Of String), _
    result As ReadOnlyCollection(Of QuantityDiscountLevel) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim offerIds As IEnumerable(Of String)
Dim result As ReadOnlyCollection(Of QuantityDiscountLevel)

instance.PutMultipleBuyDiscountLinesByOfferIds(offerIds, _
    result)
```

``` csharp
void PutMultipleBuyDiscountLinesByOfferIds(
    IEnumerable<string> offerIds,
    ReadOnlyCollection<QuantityDiscountLevel> result
)
```

``` c++
void PutMultipleBuyDiscountLinesByOfferIds(
    IEnumerable<String^>^ offerIds, 
    ReadOnlyCollection<QuantityDiscountLevel^>^ result
)
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

