---
title: ICachedPricingDataManager.PutRetailDiscountPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutRetailDiscountPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutRetailDiscountPriceGroups(System.Collections.Generic.ISet{System.String},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountPriceGroup})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putretaildiscountpricegroups(v=AX.60)
ms:contentKeyID: 62214536
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutRetailDiscountPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# PutRetailDiscountPriceGroups Method

Stores the result of a call to get the retail discount price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutRetailDiscountPriceGroups ( _
    offerIds As ISet(Of String), _
    result As ReadOnlyCollection(Of RetailDiscountPriceGroup) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim offerIds As ISet(Of String)
Dim result As ReadOnlyCollection(Of RetailDiscountPriceGroup)

instance.PutRetailDiscountPriceGroups(offerIds, _
    result)
```

``` csharp
void PutRetailDiscountPriceGroups(
    ISet<string> offerIds,
    ReadOnlyCollection<RetailDiscountPriceGroup> result
)
```

``` c++
void PutRetailDiscountPriceGroups(
    ISet<String^>^ offerIds, 
    ReadOnlyCollection<RetailDiscountPriceGroup^>^ result
)
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RetailDiscountPriceGroup](retaildiscountpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

