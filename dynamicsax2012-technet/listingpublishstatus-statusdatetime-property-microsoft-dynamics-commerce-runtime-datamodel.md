---
title: ListingPublishStatus.StatusDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatusDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.StatusDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.listingpublishstatus.statusdatetime(v=AX.60)
ms:contentKeyID: 49823045
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.StatusDateTime
dev_langs:
- CSharp
- C++
- VB
---

# StatusDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the UTC date and time when the status was captured.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATUSDATETIME")> _
<DataMemberAttribute> _
Public Property StatusDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As ListingPublishStatus
Dim value As DateTimeOffset

value = instance.StatusDateTime

instance.StatusDateTime = value
```

``` csharp
[ColumnAttribute("STATUSDATETIME")]
[DataMemberAttribute]
public DateTimeOffset StatusDateTime { get; set; }
```

``` c++
[ColumnAttribute(L"STATUSDATETIME")]
[DataMemberAttribute]
public:
property DateTimeOffset StatusDateTime {
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

