---
title: ShippingDataManager.GetItemDimensions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemDimensions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetItemDimensions(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getitemdimensions(v=AX.60)
ms:contentKeyID: 49834243
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetItemDimensions
dev_langs:
- CSharp
- C++
- VB
---

# GetItemDimensions Method

Gets the item dimensions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemDimensions ( _
    itemIds As IEnumerable(Of String), _
    columns As ColumnSet _
) As ReadOnlyCollection(Of ItemDimensions)
'Usage
Dim instance As ShippingDataManager
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
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ItemDimensions](itemdimensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of item identifiers along with their dimensions.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

