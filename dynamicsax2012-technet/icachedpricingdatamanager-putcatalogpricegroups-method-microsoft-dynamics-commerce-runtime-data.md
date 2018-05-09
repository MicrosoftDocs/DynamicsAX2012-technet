---
title: ICachedPricingDataManager.PutCatalogPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutCatalogPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutCatalogPriceGroups(System.Collections.Generic.ISet{System.Int64},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogPriceGroup})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putcatalogpricegroups(v=AX.60)
ms:contentKeyID: 62210291
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutCatalogPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# PutCatalogPriceGroups Method

Stores the result of a call to get the catalog price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutCatalogPriceGroups ( _
    catalogIds As ISet(Of Long), _
    result As ReadOnlyCollection(Of CatalogPriceGroup) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim catalogIds As ISet(Of Long)
Dim result As ReadOnlyCollection(Of CatalogPriceGroup)

instance.PutCatalogPriceGroups(catalogIds, _
    result)
```

``` csharp
void PutCatalogPriceGroups(
    ISet<long> catalogIds,
    ReadOnlyCollection<CatalogPriceGroup> result
)
```

``` c++
void PutCatalogPriceGroups(
    ISet<long long>^ catalogIds, 
    ReadOnlyCollection<CatalogPriceGroup^>^ result
)
```

#### Parameters

  - catalogIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CatalogPriceGroup](catalogpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

