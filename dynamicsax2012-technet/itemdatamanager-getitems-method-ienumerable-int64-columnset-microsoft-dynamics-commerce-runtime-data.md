---
title: ItemDataManager.GetItems Method (IEnumerable(Int64), ColumnSet) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItems Method (IEnumerable(Int64), ColumnSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetItems(System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemdatamanager.getitems(v=AX.60)
ms:contentKeyID: 49820186
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItems Method (IEnumerable(Int64), ColumnSet)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the items available to the current channel by their product identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItems ( _
    productIds As IEnumerable(Of Long), _
    columnSet As ColumnSet _
) As ReadOnlyCollection(Of Item)
'Usage
Dim instance As ItemDataManager
Dim productIds As IEnumerable(Of Long)
Dim columnSet As ColumnSet
Dim returnValue As ReadOnlyCollection(Of Item)

returnValue = instance.GetItems(productIds, _
    columnSet)
```

``` csharp
public ReadOnlyCollection<Item> GetItems(
    IEnumerable<long> productIds,
    ColumnSet columnSet
)
```

``` c++
public:
virtual ReadOnlyCollection<Item^>^ GetItems(
    IEnumerable<long long>^ productIds, 
    ColumnSet^ columnSet
) sealed
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of items or an empty list if no matching record could be found.  

#### Implements

[IItemDataManager.GetItems(IEnumerable\<Int64\>, ColumnSet)](iitemdatamanager-getitems-method-ienumerable-int64-columnset-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ItemDataManager Class](itemdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetItems Overload](itemdatamanager-getitems-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

