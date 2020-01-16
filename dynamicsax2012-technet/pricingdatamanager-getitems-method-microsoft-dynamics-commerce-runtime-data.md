---
title: PricingDataManager.GetItems Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetItems(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.getitems(v=AX.60)
ms:contentKeyID: 62211849
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetItems
dev_langs:
- CSharp
- C++
- VB
---

# GetItems Method

Gets the items using the specified item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItems ( _
    itemIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of Item)
'Usage
Dim instance As PricingDataManager
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
The collection of items.  

#### Implements

[IPricingDataManager.GetItems(IEnumerable\<String\>)](ipricingdatamanager-getitems-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

