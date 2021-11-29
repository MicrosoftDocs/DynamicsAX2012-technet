---
title: ProductManager.GetItems Method (IEnumerable(Int64), ColumnSet) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetItems Method (IEnumerable(Int64), ColumnSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetItems(System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getitems(v=AX.60)
ms:contentKeyID: 49850728
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItems Method (IEnumerable(Int64), ColumnSet)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the items by unique record identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetItems ( _
    recordIds As IEnumerable(Of Long), _
    columnSet As ColumnSet _
) As ReadOnlyCollection(Of Item)
'Usage
Dim instance As ProductManager
Dim recordIds As IEnumerable(Of Long)
Dim columnSet As ColumnSet
Dim returnValue As ReadOnlyCollection(Of Item)

returnValue = instance.GetItems(recordIds, _
    columnSet)
```

``` csharp
public ReadOnlyCollection<Item> GetItems(
    IEnumerable<long> recordIds,
    ColumnSet columnSet
)
```

``` c++
public:
ReadOnlyCollection<Item^>^ GetItems(
    IEnumerable<long long>^ recordIds, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - recordIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of items or an empty list if no matching record could be found.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetItems Overload](productmanager-getitems-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

