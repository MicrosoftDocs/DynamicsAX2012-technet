---
title: IPricingDataManagerV2.GetRetailDiscountPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetRetailDiscountPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetRetailDiscountPriceGroups(System.Collections.Generic.ISet{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.getretaildiscountpricegroups(v=AX.60)
ms:contentKeyID: 62212585
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetRetailDiscountPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetRetailDiscountPriceGroups Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets retail discount price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetRetailDiscountPriceGroups ( _
    offerIds As ISet(Of String) _
) As ReadOnlyCollection(Of RetailDiscountPriceGroup)
'Usage
Dim instance As IPricingDataManagerV2
Dim offerIds As ISet(Of String)
Dim returnValue As ReadOnlyCollection(Of RetailDiscountPriceGroup)

returnValue = instance.GetRetailDiscountPriceGroups(offerIds)
```

``` csharp
ReadOnlyCollection<RetailDiscountPriceGroup> GetRetailDiscountPriceGroups(
    ISet<string> offerIds
)
```

``` c++
ReadOnlyCollection<RetailDiscountPriceGroup^>^ GetRetailDiscountPriceGroups(
    ISet<String^>^ offerIds
)
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RetailDiscountPriceGroup](retaildiscountpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of retail discount price groups.  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

