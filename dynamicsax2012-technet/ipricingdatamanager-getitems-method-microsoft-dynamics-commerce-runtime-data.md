---
title: IPricingDataManager.GetItems Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetItems(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager.getitems(v=AX.60)
ms:contentKeyID: 62214780
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetItems
dev_langs:
- CSharp
- C++
- VB
---

# GetItems Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the items using the specified item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetItems ( _
    itemIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of Item)
'Usage
Dim instance As IPricingDataManager
Dim itemIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of Item)

returnValue = instance.GetItems(itemIds)
```

``` csharp
ReadOnlyCollection<Item> GetItems(
    IEnumerable<string> itemIds
)
```

``` c++
ReadOnlyCollection<Item^>^ GetItems(
    IEnumerable<String^>^ itemIds
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of items.  

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

