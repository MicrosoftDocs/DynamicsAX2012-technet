---
title: ProductManager.GetItems Method (IEnumerable(String), ColumnSet) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetItems Method (IEnumerable(String), ColumnSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetItems(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.productmanager.getitems(v=AX.60)
ms:contentKeyID: 49856247
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItems Method (IEnumerable(String), ColumnSet)

Gets the items using the specified item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetItems ( _
    itemIds As IEnumerable(Of String), _
    columnSet As ColumnSet _
) As ReadOnlyCollection(Of Item)
'Usage
Dim instance As ProductManager
Dim itemIds As IEnumerable(Of String)
Dim columnSet As ColumnSet
Dim returnValue As ReadOnlyCollection(Of Item)

returnValue = instance.GetItems(itemIds, _
    columnSet)
```

``` csharp
public ReadOnlyCollection<Item> GetItems(
    IEnumerable<string> itemIds,
    ColumnSet columnSet
)
```

``` c++
public:
ReadOnlyCollection<Item^>^ GetItems(
    IEnumerable<String^>^ itemIds, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of items.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetItems Overload](productmanager-getitems-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

