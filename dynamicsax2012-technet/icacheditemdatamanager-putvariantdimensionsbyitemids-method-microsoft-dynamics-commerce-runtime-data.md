---
title: ICachedItemDataManager.PutVariantDimensionsByItemIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutVariantDimensionsByItemIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutVariantDimensionsByItemIds(System.Collections.Generic.IEnumerable{System.String},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icacheditemdatamanager.putvariantdimensionsbyitemids(v=AX.60)
ms:contentKeyID: 62209492
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutVariantDimensionsByItemIds
dev_langs:
- CSharp
- C++
- VB
---

# PutVariantDimensionsByItemIds Method

Stores the variant dimensions populated for the given dimension Ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutVariantDimensionsByItemIds ( _
    inventoryDimensionIds As IEnumerable(Of String), _
    result As ReadOnlyCollection(Of ProductVariant) _
)
'Usage
Dim instance As ICachedItemDataManager
Dim inventoryDimensionIds As IEnumerable(Of String)
Dim result As ReadOnlyCollection(Of ProductVariant)

instance.PutVariantDimensionsByItemIds(inventoryDimensionIds, _
    result)
```

``` csharp
void PutVariantDimensionsByItemIds(
    IEnumerable<string> inventoryDimensionIds,
    ReadOnlyCollection<ProductVariant> result
)
```

``` c++
void PutVariantDimensionsByItemIds(
    IEnumerable<String^>^ inventoryDimensionIds, 
    ReadOnlyCollection<ProductVariant^>^ result
)
```

#### Parameters

  - inventoryDimensionIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedItemDataManager Interface](icacheditemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

