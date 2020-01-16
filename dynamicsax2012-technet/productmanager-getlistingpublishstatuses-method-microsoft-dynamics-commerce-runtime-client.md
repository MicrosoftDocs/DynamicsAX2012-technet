---
title: ProductManager.GetListingPublishStatuses Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetListingPublishStatuses Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetListingPublishStatuses(System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getlistingpublishstatuses(v=AX.60)
ms:contentKeyID: 62212487
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetListingPublishStatuses
dev_langs:
- CSharp
- C++
- VB
---

# GetListingPublishStatuses Method

Gets the collection of listing publish statuses matching the specified listing identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetListingPublishStatuses ( _
    listingIds As IEnumerable(Of Long), _
    columnSet As ColumnSet _
) As ReadOnlyCollection(Of ListingPublishStatus)
'Usage
Dim instance As ProductManager
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
The list of listing publish statuses matching the provided listing identifiers.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

