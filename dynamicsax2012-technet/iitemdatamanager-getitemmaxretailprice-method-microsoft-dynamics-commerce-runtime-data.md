---
title: IItemDataManager.GetItemMaxRetailPrice Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemMaxRetailPrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IItemDataManager.GetItemMaxRetailPrice(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.iitemdatamanager.getitemmaxretailprice(v=AX.60)
ms:contentKeyID: 62214155
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IItemDataManager.GetItemMaxRetailPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetItemMaxRetailPrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item's max retail price using the specified item identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetItemMaxRetailPrice ( _
    itemId As String, _
    columnSet As ColumnSet _
) As ItemMaxRetailPriceIndia
'Usage
Dim instance As IItemDataManager
Dim itemId As String
Dim columnSet As ColumnSet
Dim returnValue As ItemMaxRetailPriceIndia

returnValue = instance.GetItemMaxRetailPrice(itemId, _
    columnSet)
```

``` csharp
ItemMaxRetailPriceIndia GetItemMaxRetailPrice(
    string itemId,
    ColumnSet columnSet
)
```

``` c++
ItemMaxRetailPriceIndia^ GetItemMaxRetailPrice(
    String^ itemId, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemMaxRetailPriceIndia](itemmaxretailpriceindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item max retail price.  

## See Also

#### Reference

[IItemDataManager Interface](iitemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

