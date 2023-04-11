---
title: ProductManager.GetItemBarcodes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetItemBarcodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetItemBarcodes(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getitembarcodes(v=AX.60)
ms:contentKeyID: 62210037
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetItemBarcodes
dev_langs:
- CSharp
- C++
- VB
---

# GetItemBarcodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item barcodes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemBarcodes ( _
    itemIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of ItemBarcode)
'Usage
Dim instance As ProductManager
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
ReadOnlyCollection<ItemBarcode^>^ GetItemBarcodes(
    IEnumerable<String^>^ itemIds
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of barcode along with item identifiers.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

