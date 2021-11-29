---
title: IPricingDataManagerV2.GetCatalogPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCatalogPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetCatalogPriceGroups(System.Collections.Generic.ISet{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.getcatalogpricegroups(v=AX.60)
ms:contentKeyID: 62202004
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetCatalogPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetCatalogPriceGroups Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the catalog price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetCatalogPriceGroups ( _
    catalogIds As ISet(Of Long) _
) As ReadOnlyCollection(Of CatalogPriceGroup)
'Usage
Dim instance As IPricingDataManagerV2
Dim catalogIds As ISet(Of Long)
Dim returnValue As ReadOnlyCollection(Of CatalogPriceGroup)

returnValue = instance.GetCatalogPriceGroups(catalogIds)
```

``` csharp
ReadOnlyCollection<CatalogPriceGroup> GetCatalogPriceGroups(
    ISet<long> catalogIds
)
```

``` c++
ReadOnlyCollection<CatalogPriceGroup^>^ GetCatalogPriceGroups(
    ISet<long long>^ catalogIds
)
```

#### Parameters

  - catalogIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CatalogPriceGroup](catalogpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of catalog price groups.  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

