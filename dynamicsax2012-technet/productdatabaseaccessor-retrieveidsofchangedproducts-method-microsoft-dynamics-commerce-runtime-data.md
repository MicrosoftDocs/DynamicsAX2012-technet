---
title: ProductDatabaseAccessor.RetrieveIdsOfChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: RetrieveIdsOfChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.RetrieveIdsOfChangedProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria,System.Int64@,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet@,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.retrieveidsofchangedproducts(v=AX.60)
ms:contentKeyID: 62202999
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.RetrieveIdsOfChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# RetrieveIdsOfChangedProducts Method

Retrieves the ids of products that satisfy the specified change-tracking criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function RetrieveIdsOfChangedProducts ( _
    queryCriteria As ChangedProductsSearchCriteria, _
    <OutAttribute> ByRef currentMarker As Long, _
    <OutAttribute> ByRef currentWatermark As ProductChangeTrackingAnchorSet, _
    <OutAttribute> ByRef nextWatermark As ProductChangeTrackingAnchorSet _
) As ReadOnlyCollection(Of CommerceEntityChangeTrackingInformation)
'Usage
Dim instance As ProductDatabaseAccessor
Dim queryCriteria As ChangedProductsSearchCriteria
Dim currentMarker As Long
Dim currentWatermark As ProductChangeTrackingAnchorSet
Dim nextWatermark As ProductChangeTrackingAnchorSet
Dim returnValue As ReadOnlyCollection(Of CommerceEntityChangeTrackingInformation)

returnValue = instance.RetrieveIdsOfChangedProducts(queryCriteria, _
    currentMarker, currentWatermark, _
    nextWatermark)
```

``` csharp
public ReadOnlyCollection<CommerceEntityChangeTrackingInformation> RetrieveIdsOfChangedProducts(
    ChangedProductsSearchCriteria queryCriteria,
    out long currentMarker,
    out ProductChangeTrackingAnchorSet currentWatermark,
    out ProductChangeTrackingAnchorSet nextWatermark
)
```

``` c++
public:
ReadOnlyCollection<CommerceEntityChangeTrackingInformation^>^ RetrieveIdsOfChangedProducts(
    ChangedProductsSearchCriteria^ queryCriteria, 
    [OutAttribute] long long% currentMarker, 
    [OutAttribute] ProductChangeTrackingAnchorSet^% currentWatermark, 
    [OutAttribute] ProductChangeTrackingAnchorSet^% nextWatermark
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - currentMarker  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - currentWatermark  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - nextWatermark  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CommerceEntityChangeTrackingInformation](commerceentitychangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of products ids.  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

