---
title: UnableToResolveListingIdsNotification.ListingIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ListingIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToResolveListingIdsNotification.ListingIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unabletoresolvelistingidsnotification.listingids(v=AX.60)
ms:contentKeyID: 65322579
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToResolveListingIdsNotification.ListingIds
dev_langs:
- CSharp
- C++
- VB
---

# ListingIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the listing identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingIds As ReadOnlyCollection(Of Long)
    Get
    Private Set
'Usage
Dim instance As UnableToResolveListingIdsNotification
Dim value As ReadOnlyCollection(Of Long)

value = instance.ListingIds
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<long> ListingIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<long long>^ ListingIds {
    ReadOnlyCollection<long long>^ get ();
    private: void set (ReadOnlyCollection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[UnableToResolveListingIdsNotification Class](unabletoresolvelistingidsnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

