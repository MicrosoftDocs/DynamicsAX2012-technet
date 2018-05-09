---
title: ProductL2CacheDataStoreAccessor.PutLinkedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutLinkedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutLinkedProducts(System.Collections.Generic.IEnumerable{System.Int64},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.LinkedProduct})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.putlinkedproducts(v=AX.60)
ms:contentKeyID: 62207626
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutLinkedProducts
dev_langs:
- CSharp
- C++
- VB
---

# PutLinkedProducts Method

Store the result of a query for linked products of the given set of product identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutLinkedProducts ( _
    productIds As IEnumerable(Of Long), _
    result As ReadOnlyCollection(Of LinkedProduct) _
)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim productIds As IEnumerable(Of Long)
Dim result As ReadOnlyCollection(Of LinkedProduct)

instance.PutLinkedProducts(productIds, _
    result)
```

``` csharp
public void PutLinkedProducts(
    IEnumerable<long> productIds,
    ReadOnlyCollection<LinkedProduct> result
)
```

``` c++
public:
virtual void PutLinkedProducts(
    IEnumerable<long long>^ productIds, 
    ReadOnlyCollection<LinkedProduct^>^ result
) sealed
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[ICachedProductDataManager.PutLinkedProducts(IEnumerable\<Int64\>, ReadOnlyCollection\<LinkedProduct\>)](icachedproductdatamanager-putlinkedproducts-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

