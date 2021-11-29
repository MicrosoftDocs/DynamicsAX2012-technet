---
title: ProductManager.GetItemDimensions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetItemDimensions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetItemDimensions(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getitemdimensions(v=AX.60)
ms:contentKeyID: 62208330
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetItemDimensions
dev_langs:
- CSharp
- C++
- VB
---

# GetItemDimensions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item dimensions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemDimensions ( _
    itemIds As IEnumerable(Of String), _
    columns As ColumnSet _
) As ReadOnlyCollection(Of ItemDimensions)
'Usage
Dim instance As ProductManager
Dim itemIds As IEnumerable(Of String)
Dim columns As ColumnSet
Dim returnValue As ReadOnlyCollection(Of ItemDimensions)

returnValue = instance.GetItemDimensions(itemIds, _
    columns)
```

``` csharp
public ReadOnlyCollection<ItemDimensions> GetItemDimensions(
    IEnumerable<string> itemIds,
    ColumnSet columns
)
```

``` c++
public:
ReadOnlyCollection<ItemDimensions^>^ GetItemDimensions(
    IEnumerable<String^>^ itemIds, 
    ColumnSet^ columns
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemDimensions](itemdimensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of item identifiers along with their dimensions.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

