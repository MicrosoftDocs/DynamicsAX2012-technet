---
title: ICachedItemDataManager.PutItemBarcodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutItemBarcodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutItemBarcodes(System.Collections.Generic.IEnumerable{System.String},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icacheditemdatamanager.putitembarcodes(v=AX.60)
ms:contentKeyID: 62213244
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutItemBarcodes
dev_langs:
- CSharp
- C++
- VB
---

# PutItemBarcodes Method

Stores barcode information for the given set of Items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutItemBarcodes ( _
    itemIds As IEnumerable(Of String), _
    result As ReadOnlyCollection(Of ItemBarcode) _
)
'Usage
Dim instance As ICachedItemDataManager
Dim itemIds As IEnumerable(Of String)
Dim result As ReadOnlyCollection(Of ItemBarcode)

instance.PutItemBarcodes(itemIds, result)
```

``` csharp
void PutItemBarcodes(
    IEnumerable<string> itemIds,
    ReadOnlyCollection<ItemBarcode> result
)
```

``` c++
void PutItemBarcodes(
    IEnumerable<String^>^ itemIds, 
    ReadOnlyCollection<ItemBarcode^>^ result
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedItemDataManager Interface](icacheditemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

