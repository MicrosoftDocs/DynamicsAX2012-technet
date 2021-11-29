---
title: ProductDataManager.GetProductCatalogAssociations Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductCatalogAssociations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetProductCatalogAssociations(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.getproductcatalogassociations(v=AX.60)
ms:contentKeyID: 62208271
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetProductCatalogAssociations
dev_langs:
- CSharp
- C++
- VB
---

# GetProductCatalogAssociations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the active catalogs for the specified products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductCatalogAssociations ( _
    productIds As IEnumerable(Of Long) _
) As ReadOnlyCollection(Of ProductCatalogAssociation)
'Usage
Dim instance As ProductDataManager
Dim productIds As IEnumerable(Of Long)
Dim returnValue As ReadOnlyCollection(Of ProductCatalogAssociation)

returnValue = instance.GetProductCatalogAssociations(productIds)
```

``` csharp
public ReadOnlyCollection<ProductCatalogAssociation> GetProductCatalogAssociations(
    IEnumerable<long> productIds
)
```

``` c++
public:
virtual ReadOnlyCollection<ProductCatalogAssociation^>^ GetProductCatalogAssociations(
    IEnumerable<long long>^ productIds
) sealed
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalogAssociation](productcatalogassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of catalog ids for the specified products.  

#### Implements

[IProductDataManager.GetProductCatalogAssociations(IEnumerable\<Int64\>)](iproductdatamanager-getproductcatalogassociations-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

