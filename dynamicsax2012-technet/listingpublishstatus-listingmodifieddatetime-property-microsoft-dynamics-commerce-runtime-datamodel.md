---
title: ListingPublishStatus.ListingModifiedDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ListingModifiedDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.ListingModifiedDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.listingpublishstatus.listingmodifieddatetime(v=AX.60)
ms:contentKeyID: 49843083
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.ListingModifiedDateTime
dev_langs:
- CSharp
- C++
- VB
---

# ListingModifiedDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the listing modified date time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LISTINGMODIFIEDDATETIME")> _
<DataMemberAttribute> _
Public Property ListingModifiedDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As ListingPublishStatus
Dim value As DateTimeOffset

value = instance.ListingModifiedDateTime

instance.ListingModifiedDateTime = value
```

``` csharp
[ColumnAttribute("LISTINGMODIFIEDDATETIME")]
[DataMemberAttribute]
public DateTimeOffset ListingModifiedDateTime { get; set; }
```

``` c++
[ColumnAttribute(L"LISTINGMODIFIEDDATETIME")]
[DataMemberAttribute]
public:
property DateTimeOffset ListingModifiedDateTime {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ListingPublishStatus Class](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

