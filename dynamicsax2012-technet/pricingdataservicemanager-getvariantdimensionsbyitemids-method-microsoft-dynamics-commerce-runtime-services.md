---
title: PricingDataServiceManager.GetVariantDimensionsByItemIds Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetVariantDimensionsByItemIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetVariantDimensionsByItemIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getvariantdimensionsbyitemids(v=AX.60)
ms:contentKeyID: 65321601
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetVariantDimensionsByItemIds
dev_langs:
- CSharp
- C++
- VB
---

# GetVariantDimensionsByItemIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetVariantDimensionsByItemIds ( _
    inventoryDimensionIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of ProductVariant)
'Usage
Dim instance As PricingDataServiceManager
Dim inventoryDimensionIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of ProductVariant)

returnValue = instance.GetVariantDimensionsByItemIds(inventoryDimensionIds)
```

``` csharp
public ReadOnlyCollection<ProductVariant> GetVariantDimensionsByItemIds(
    IEnumerable<string> inventoryDimensionIds
)
```

``` c++
public:
virtual ReadOnlyCollection<ProductVariant^>^ GetVariantDimensionsByItemIds(
    IEnumerable<String^>^ inventoryDimensionIds
) sealed
```

#### Parameters

  - inventoryDimensionIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManagerV2.GetVariantDimensionsByItemIds(IEnumerable\<String\>)](ipricingdatamanagerv2-getvariantdimensionsbyitemids-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

