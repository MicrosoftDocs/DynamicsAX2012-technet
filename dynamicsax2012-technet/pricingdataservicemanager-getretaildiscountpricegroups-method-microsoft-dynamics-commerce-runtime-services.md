---
title: PricingDataServiceManager.GetRetailDiscountPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetRetailDiscountPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetRetailDiscountPriceGroups(System.Collections.Generic.ISet{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getretaildiscountpricegroups(v=AX.60)
ms:contentKeyID: 65320981
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetRetailDiscountPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetRetailDiscountPriceGroups Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetRetailDiscountPriceGroups ( _
    offerIds As ISet(Of String) _
) As ReadOnlyCollection(Of RetailDiscountPriceGroup)
'Usage
Dim instance As PricingDataServiceManager
Dim offerIds As ISet(Of String)
Dim returnValue As ReadOnlyCollection(Of RetailDiscountPriceGroup)

returnValue = instance.GetRetailDiscountPriceGroups(offerIds)
```

``` csharp
public ReadOnlyCollection<RetailDiscountPriceGroup> GetRetailDiscountPriceGroups(
    ISet<string> offerIds
)
```

``` c++
public:
virtual ReadOnlyCollection<RetailDiscountPriceGroup^>^ GetRetailDiscountPriceGroups(
    ISet<String^>^ offerIds
) sealed
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[RetailDiscountPriceGroup](retaildiscountpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManagerV2.GetRetailDiscountPriceGroups(ISet\<String\>)](ipricingdatamanagerv2-getretaildiscountpricegroups-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

