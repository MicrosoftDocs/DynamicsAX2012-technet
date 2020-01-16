---
title: ProductDatabaseAccessor.GetNextBatchListingPublishStatuses Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetNextBatchListingPublishStatuses Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.GetNextBatchListingPublishStatuses(Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.getnextbatchlistingpublishstatuses(v=AX.60)
ms:contentKeyID: 65320306
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.GetNextBatchListingPublishStatuses
dev_langs:
- CSharp
- C++
- VB
---

# GetNextBatchListingPublishStatuses Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetNextBatchListingPublishStatuses ( _
    actionStatus As ListingPublishingActionStatus, _
    lastChannelBatchId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ListingPublishStatus)
'Usage
Dim instance As ProductDatabaseAccessor
Dim actionStatus As ListingPublishingActionStatus
Dim lastChannelBatchId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ListingPublishStatus)

returnValue = instance.GetNextBatchListingPublishStatuses(actionStatus, _
    lastChannelBatchId, settings)
```

``` csharp
public ReadOnlyCollection<ListingPublishStatus> GetNextBatchListingPublishStatuses(
    ListingPublishingActionStatus actionStatus,
    string lastChannelBatchId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<ListingPublishStatus^>^ GetNextBatchListingPublishStatuses(
    ListingPublishingActionStatus actionStatus, 
    String^ lastChannelBatchId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - actionStatus  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus](listingpublishingactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - lastChannelBatchId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ListingPublishStatus](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

