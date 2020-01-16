---
title: PricingDatabaseAccessor.GetRetailDiscountPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetRetailDiscountPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetRetailDiscountPriceGroups(System.Collections.Generic.ISet{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getretaildiscountpricegroups(v=AX.60)
ms:contentKeyID: 62208751
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetRetailDiscountPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetRetailDiscountPriceGroups Method

Gets retail discount price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetRetailDiscountPriceGroups ( _
    offerIds As ISet(Of String) _
) As ReadOnlyCollection(Of RetailDiscountPriceGroup)
'Usage
Dim instance As PricingDatabaseAccessor
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
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RetailDiscountPriceGroup](retaildiscountpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of retail discount price groups.  

#### Implements

[IPricingDataManagerV2.GetRetailDiscountPriceGroups(ISet\<String\>)](ipricingdatamanagerv2-getretaildiscountpricegroups-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

