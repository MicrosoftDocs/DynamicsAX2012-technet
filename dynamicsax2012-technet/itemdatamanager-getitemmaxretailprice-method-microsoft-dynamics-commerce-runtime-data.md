---
title: ItemDataManager.GetItemMaxRetailPrice Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemMaxRetailPrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetItemMaxRetailPrice(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemdatamanager.getitemmaxretailprice(v=AX.60)
ms:contentKeyID: 62215120
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetItemMaxRetailPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetItemMaxRetailPrice Method

Gets the item's max retail price using the specified item identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemMaxRetailPrice ( _
    itemId As String, _
    columnSet As ColumnSet _
) As ItemMaxRetailPriceIndia
'Usage
Dim instance As ItemDataManager
Dim itemId As String
Dim columnSet As ColumnSet
Dim returnValue As ItemMaxRetailPriceIndia

returnValue = instance.GetItemMaxRetailPrice(itemId, _
    columnSet)
```

``` csharp
public ItemMaxRetailPriceIndia GetItemMaxRetailPrice(
    string itemId,
    ColumnSet columnSet
)
```

``` c++
public:
virtual ItemMaxRetailPriceIndia^ GetItemMaxRetailPrice(
    String^ itemId, 
    ColumnSet^ columnSet
) sealed
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

#### Implements

[IItemDataManager.GetItemMaxRetailPrice(String, ColumnSet)](iitemdatamanager-getitemmaxretailprice-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ItemDataManager Class](itemdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

