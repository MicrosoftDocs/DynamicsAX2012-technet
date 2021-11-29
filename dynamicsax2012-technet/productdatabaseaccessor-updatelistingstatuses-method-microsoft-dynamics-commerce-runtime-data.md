---
title: ProductDatabaseAccessor.UpdateListingStatuses Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: UpdateListingStatuses Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.UpdateListingStatuses(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.updatelistingstatuses(v=AX.60)
ms:contentKeyID: 62211746
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.UpdateListingStatuses
dev_langs:
- CSharp
- C++
- VB
---

# UpdateListingStatuses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the listing statuses.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateListingStatuses ( _
    statusList As IEnumerable(Of ListingPublishStatus) _
)
'Usage
Dim instance As ProductDatabaseAccessor
Dim statusList As IEnumerable(Of ListingPublishStatus)

instance.UpdateListingStatuses(statusList)
```

``` csharp
public void UpdateListingStatuses(
    IEnumerable<ListingPublishStatus> statusList
)
```

``` c++
public:
void UpdateListingStatuses(
    IEnumerable<ListingPublishStatus^>^ statusList
)
```

#### Parameters

  - statusList  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingPublishStatus](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

