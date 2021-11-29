---
title: ICachedItemDataManager.PutVariants Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutVariants Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutVariants(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension},Microsoft.Dynamics.Commerce.Runtime.ColumnSet,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icacheditemdatamanager.putvariants(v=AX.60)
ms:contentKeyID: 62208509
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutVariants
dev_langs:
- CSharp
- C++
- VB
---

# PutVariants Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Stores the product variants for the given set of item variant inventory dimension identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutVariants ( _
    itemVariants As IEnumerable(Of ItemVariantInventoryDimension), _
    columnSet As ColumnSet, _
    result As ReadOnlyCollection(Of ProductVariant) _
)
'Usage
Dim instance As ICachedItemDataManager
Dim itemVariants As IEnumerable(Of ItemVariantInventoryDimension)
Dim columnSet As ColumnSet
Dim result As ReadOnlyCollection(Of ProductVariant)

instance.PutVariants(itemVariants, columnSet, _
    result)
```

``` csharp
void PutVariants(
    IEnumerable<ItemVariantInventoryDimension> itemVariants,
    ColumnSet columnSet,
    ReadOnlyCollection<ProductVariant> result
)
```

``` c++
void PutVariants(
    IEnumerable<ItemVariantInventoryDimension^>^ itemVariants, 
    ColumnSet^ columnSet, 
    ReadOnlyCollection<ProductVariant^>^ result
)
```

#### Parameters

  - itemVariants  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedItemDataManager Interface](icacheditemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

