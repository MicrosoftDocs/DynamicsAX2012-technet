---
title: ListingPublishStatus.PublishStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PublishStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.PublishStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.listingpublishstatus.publishstatus(v=AX.60)
ms:contentKeyID: 49846071
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.PublishStatus
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatus Property

Gets or sets the publishing status of the listing in the channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ACTIONSTATUS")> _
<DataMemberAttribute> _
Public Property PublishStatus As ListingPublishingActionStatus
    Get
    Set
'Usage
Dim instance As ListingPublishStatus
Dim value As ListingPublishingActionStatus

value = instance.PublishStatus

instance.PublishStatus = value
```

``` csharp
[ColumnAttribute("ACTIONSTATUS")]
[DataMemberAttribute]
public ListingPublishingActionStatus PublishStatus { get; set; }
```

``` c++
[ColumnAttribute(L"ACTIONSTATUS")]
[DataMemberAttribute]
public:
property ListingPublishingActionStatus PublishStatus {
    ListingPublishingActionStatus get ();
    void set (ListingPublishingActionStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus](listingpublishingactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ListingPublishingActionStatus](listingpublishingactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ListingPublishStatus Class](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

