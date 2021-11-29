---
title: ItemDataManager.GetItemBarcodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemBarcodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetItemBarcodes(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemdatamanager.getitembarcodes(v=AX.60)
ms:contentKeyID: 62210736
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetItemBarcodes
dev_langs:
- CSharp
- C++
- VB
---

# GetItemBarcodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets barcode information for the given set of Items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemBarcodes ( _
    itemIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of ItemBarcode)
'Usage
Dim instance As ItemDataManager
Dim itemIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of ItemBarcode)

returnValue = instance.GetItemBarcodes(itemIds)
```

``` csharp
public ReadOnlyCollection<ItemBarcode> GetItemBarcodes(
    IEnumerable<string> itemIds
)
```

``` c++
public:
virtual ReadOnlyCollection<ItemBarcode^>^ GetItemBarcodes(
    IEnumerable<String^>^ itemIds
) sealed
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of item barcode information.  

#### Implements

[IItemDataManager.GetItemBarcodes(IEnumerable\<String\>)](iitemdatamanager-getitembarcodes-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ItemDataManager Class](itemdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

