---
title: PricingDatabaseAccessor.GetVariants Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetVariants Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetVariants(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getvariants(v=AX.60)
ms:contentKeyID: 62203439
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetVariants
dev_langs:
- CSharp
- C++
- VB
---

# GetVariants Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of product variants.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetVariants ( _
    itemVariants As IEnumerable(Of ItemVariantInventoryDimension), _
    columnSet As ColumnSet _
) As ReadOnlyCollection(Of ProductVariant)
'Usage
Dim instance As PricingDatabaseAccessor
Dim itemVariants As IEnumerable(Of ItemVariantInventoryDimension)
Dim columnSet As ColumnSet
Dim returnValue As ReadOnlyCollection(Of ProductVariant)

returnValue = instance.GetVariants(itemVariants, _
    columnSet)
```

``` csharp
public ReadOnlyCollection<ProductVariant> GetVariants(
    IEnumerable<ItemVariantInventoryDimension> itemVariants,
    ColumnSet columnSet
)
```

``` c++
public:
virtual ReadOnlyCollection<ProductVariant^>^ GetVariants(
    IEnumerable<ItemVariantInventoryDimension^>^ itemVariants, 
    ColumnSet^ columnSet
) sealed
```

#### Parameters

  - itemVariants  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of product variants.  

#### Implements

[IPricingDataManagerV2.GetVariants(IEnumerable\<ItemVariantInventoryDimension\>, ColumnSet)](ipricingdatamanagerv2-getvariants-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

