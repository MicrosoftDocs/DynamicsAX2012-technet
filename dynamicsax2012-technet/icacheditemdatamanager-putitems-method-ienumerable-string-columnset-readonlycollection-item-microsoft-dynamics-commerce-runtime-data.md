---
title: ICachedItemDataManager.PutItems Method (IEnumerable(String), ColumnSet, ReadOnlyCollection(Item)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutItems Method (IEnumerable(String), ColumnSet, ReadOnlyCollection(Item))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutItems(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Item})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icacheditemdatamanager.putitems(v=AX.60)
ms:contentKeyID: 62209512
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutItems Method (IEnumerable(String), ColumnSet, ReadOnlyCollection(Item))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Stores the items using the specified item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutItems ( _
    itemIds As IEnumerable(Of String), _
    columnSet As ColumnSet, _
    result As ReadOnlyCollection(Of Item) _
)
'Usage
Dim instance As ICachedItemDataManager
Dim itemIds As IEnumerable(Of String)
Dim columnSet As ColumnSet
Dim result As ReadOnlyCollection(Of Item)

instance.PutItems(itemIds, columnSet, _
    result)
```

``` csharp
void PutItems(
    IEnumerable<string> itemIds,
    ColumnSet columnSet,
    ReadOnlyCollection<Item> result
)
```

``` c++
void PutItems(
    IEnumerable<String^>^ itemIds, 
    ColumnSet^ columnSet, 
    ReadOnlyCollection<Item^>^ result
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

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

