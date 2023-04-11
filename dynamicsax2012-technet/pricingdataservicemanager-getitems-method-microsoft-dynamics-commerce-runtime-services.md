---
title: PricingDataServiceManager.GetItems Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetItems(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getitems(v=AX.60)
ms:contentKeyID: 65322005
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetItems
dev_langs:
- CSharp
- C++
- VB
---

# GetItems Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetItems ( _
    itemIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of Item)
'Usage
Dim instance As PricingDataServiceManager
Dim itemIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of Item)

returnValue = instance.GetItems(itemIds)
```

``` csharp
public ReadOnlyCollection<Item> GetItems(
    IEnumerable<string> itemIds
)
```

``` c++
public:
virtual ReadOnlyCollection<Item^>^ GetItems(
    IEnumerable<String^>^ itemIds
) sealed
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManager.GetItems(IEnumerable\<String\>)](ipricingdatamanager-getitems-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

