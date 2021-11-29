---
title: ProductDataManager.GetListingPublishStatuses Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetListingPublishStatuses Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetListingPublishStatuses(System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.getlistingpublishstatuses(v=AX.60)
ms:contentKeyID: 62203222
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetListingPublishStatuses
dev_langs:
- CSharp
- C++
- VB
---

# GetListingPublishStatuses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the publishing status for the specified listing ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetListingPublishStatuses ( _
    listingIds As IEnumerable(Of Long), _
    columnSet As ColumnSet _
) As ReadOnlyCollection(Of ListingPublishStatus)
'Usage
Dim instance As ProductDataManager
Dim listingIds As IEnumerable(Of Long)
Dim columnSet As ColumnSet
Dim returnValue As ReadOnlyCollection(Of ListingPublishStatus)

returnValue = instance.GetListingPublishStatuses(listingIds, _
    columnSet)
```

``` csharp
public ReadOnlyCollection<ListingPublishStatus> GetListingPublishStatuses(
    IEnumerable<long> listingIds,
    ColumnSet columnSet
)
```

``` c++
public:
ReadOnlyCollection<ListingPublishStatus^>^ GetListingPublishStatuses(
    IEnumerable<long long>^ listingIds, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ListingPublishStatus](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of listing publish status codes.  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

