---
title: PricingDataServiceManager.GetCatalogPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetCatalogPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetCatalogPriceGroups(System.Collections.Generic.ISet{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getcatalogpricegroups(v=AX.60)
ms:contentKeyID: 65320744
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetCatalogPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetCatalogPriceGroups Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetCatalogPriceGroups ( _
    catalogIds As ISet(Of Long) _
) As ReadOnlyCollection(Of CatalogPriceGroup)
'Usage
Dim instance As PricingDataServiceManager
Dim catalogIds As ISet(Of Long)
Dim returnValue As ReadOnlyCollection(Of CatalogPriceGroup)

returnValue = instance.GetCatalogPriceGroups(catalogIds)
```

``` csharp
public ReadOnlyCollection<CatalogPriceGroup> GetCatalogPriceGroups(
    ISet<long> catalogIds
)
```

``` c++
public:
virtual ReadOnlyCollection<CatalogPriceGroup^>^ GetCatalogPriceGroups(
    ISet<long long>^ catalogIds
) sealed
```

#### Parameters

  - catalogIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CatalogPriceGroup](catalogpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManagerV2.GetCatalogPriceGroups(ISet\<Int64\>)](ipricingdatamanagerv2-getcatalogpricegroups-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

