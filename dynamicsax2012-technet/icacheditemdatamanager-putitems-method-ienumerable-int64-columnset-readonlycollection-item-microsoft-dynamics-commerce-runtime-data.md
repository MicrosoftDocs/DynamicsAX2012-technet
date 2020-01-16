---
title: ICachedItemDataManager.PutItems Method (IEnumerable(Int64), ColumnSet, ReadOnlyCollection(Item)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutItems Method (IEnumerable(Int64), ColumnSet, ReadOnlyCollection(Item))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutItems(System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.ColumnSet,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Item})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icacheditemdatamanager.putitems(v=AX.60)
ms:contentKeyID: 62207577
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutItems Method (IEnumerable(Int64), ColumnSet, ReadOnlyCollection(Item))

Stores the items available to the current channel by their product identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutItems ( _
    productIds As IEnumerable(Of Long), _
    columnSet As ColumnSet, _
    result As ReadOnlyCollection(Of Item) _
)
'Usage
Dim instance As ICachedItemDataManager
Dim productIds As IEnumerable(Of Long)
Dim columnSet As ColumnSet
Dim result As ReadOnlyCollection(Of Item)

instance.PutItems(productIds, columnSet, _
    result)
```

``` csharp
void PutItems(
    IEnumerable<long> productIds,
    ColumnSet columnSet,
    ReadOnlyCollection<Item> result
)
```

``` c++
void PutItems(
    IEnumerable<long long>^ productIds, 
    ColumnSet^ columnSet, 
    ReadOnlyCollection<Item^>^ result
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedItemDataManager Interface](icacheditemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[PutItems Overload](icacheditemdatamanager-putitems-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

