---
title: ProductL2CacheDataStoreAccessor.PutProductCatalogAssociations Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutProductCatalogAssociations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutProductCatalogAssociations(System.Collections.Generic.IEnumerable{System.Int64},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalogAssociation})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.putproductcatalogassociations(v=AX.60)
ms:contentKeyID: 62209928
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutProductCatalogAssociations
dev_langs:
- CSharp
- C++
- VB
---

# PutProductCatalogAssociations Method

Caches the active catalogs for the specified products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutProductCatalogAssociations ( _
    productIds As IEnumerable(Of Long), _
    result As ReadOnlyCollection(Of ProductCatalogAssociation) _
)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim productIds As IEnumerable(Of Long)
Dim result As ReadOnlyCollection(Of ProductCatalogAssociation)

instance.PutProductCatalogAssociations(productIds, _
    result)
```

``` csharp
public void PutProductCatalogAssociations(
    IEnumerable<long> productIds,
    ReadOnlyCollection<ProductCatalogAssociation> result
)
```

``` c++
public:
void PutProductCatalogAssociations(
    IEnumerable<long long>^ productIds, 
    ReadOnlyCollection<ProductCatalogAssociation^>^ result
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductCatalogAssociation](productcatalogassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

